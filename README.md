# LC3-VMs
Little Computer 3 VMs in different languages to compare them for such use-cases.
The idea is mostly to see how easy and how nice are they to write - as well as how good the tooling around them is.

## Languages
- [ ] C version from ...
- [ ] Zig
- [ ] Nim
- [ ] FORTH
- [ ] Common Lisp
- [ ] Odin?
- [ ] Rust?
- [ ] ...

### C
Using the [LC3 VM version by Justin Meiners](https://www.jmeiners.com/lc3-vm/) as the example for how to do it.

### Zig
#### *First look some time in 2022*
- Seems unnecessarily uglier and more cumbersome than the C version in multiple regards.
- I dislike how Enums work. Having to cast to and from to get the numerical value of the Enum is annoying.
  - This meant having to redesign the way the original works and making it more verbose.
- Builtin functions seem to use multiple different naming conventions.
- Dokumentation on testing had wrong/faulty examples saying test worked in a way they didn't - unsure if dokumentation bug or test framework bug.
  - All-in-all the dokumentation seems laking.
- Comp-time seems just worse than well designed macros in every way.

##### Pet peeves
- No modern language should use semicolons to end lines.
  - Anyone who thinks differently is simply wrong.
    - Not to be confused with whitespace denoting execution blocks - I don't like that either.
  - It's esepically egregious when the language compiler enforces whitespace formating making the semicolons entirely obsolete.
- I despise not being able to define unused varibales. Rapid prototyping is the most important technique when developing new software. Have at least a dev compilation flag that turns of most safety things.
- The language is highly opinionated - it robs one of multiple freedomes given by C.
  - In my opinion this disqualifies it from being called a "better C" alternative since the mindset/philosophy whilst programming it is different.
- Unnecessarily verbose - e.g. Enums, ...

#### *Second try October of 2024*
- 

