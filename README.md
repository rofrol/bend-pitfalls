# bend-pitfalls

Pitfalls of the [Bend 2](https://github.com/bendlang/bend) language and
compiler, met in real projects: `PITFALLS.md`. Each entry names the compiler
version it was seen with.

## Using it

A project imports a pinned snapshot instead of linking here, so a clone of
it stands alone: copy `PITFALLS.md` at one commit into the project (for
example as `docs/bend-pitfalls.md`), record that commit next to it, and
check the copy against it, e.g.

```sh
curl -fsSL https://raw.githubusercontent.com/rofrol/bend-pitfalls/<commit>/PITFALLS.md
```

Lessons that depend on one project's toolchain, runtime patch or effects
stay in that project.

## Adding a pitfall

One entry per pitfall, under the section it belongs to (Code, Running,
Proofs), ending with the Bend version it was seen with, e.g. `(2.0.35)`.
When a later version changes it, say so in the entry rather than deleting
it while a project still pins the old version.
