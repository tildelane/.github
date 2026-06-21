# tildelane

> **Dotfiles you can carry everywhere, and secrets you can never leak.**

The files in your home directory are the most personal infrastructure you own — the accumulated configuration of how you work, carried from machine to machine over years. The trouble is that they sit right next to your secrets, and the moment you put them under version control, one careless commit can publish a key to the world. Most dotfile tooling treats that danger as your problem to remember. The work here treats it as the tool's problem to prevent.

The premise is fail-closed governance: not a polite warning that you might be committing a secret, but a pipeline that refuses to let it happen in the first place. Sensitive material is encrypted at rest rather than trusted to discipline, configuration syncs cleanly across every machine you use, and the safe path is the only path the system will take. Security isn't a setting you remember to switch on; it's the default you cannot switch off.

The aim is the comfort of your environment following you everywhere, without the quiet dread that one of those files was the one you shouldn't have pushed.

---

<p align="center"><a href="https://tildelane.dev">tildelane.dev</a></p>
