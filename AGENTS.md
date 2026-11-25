# Agent rules

This repository is Godot 4.7.2-stable (commit `ed1daf0bf001b61586d9930840f2f1394092c079`) with our bug fixes backported. It holds no features.

- One bug fix per pull request, on the `4.7` branch. A fix carries a test that fails without it and passes with it, or, for a build fix, names the compiler, platform or option whose build it repairs.
- No feature enhancements: a new class, method, setting, module, or a change of behaviour that is not a fix waits for a Godot release that has it.
- A fix is a backport: name the commit or branch it comes from, and check first that 4.7.2 does not already fix it.
- `V-Sekai-fire/build-containers` builds a pinned commit of this branch at double precision, and changes only its containers, never this tree.
