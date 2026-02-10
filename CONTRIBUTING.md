# Contributing to T-Boyke - The "Hurt Me Plenty" Edition

Congratulations. You decided to contribute to this repository. This demonstrates either extreme courage or a concerning lack of self-preservation instinct.

Before you write a single line of code, know this: **I have a linter, and I will use it.**

These are the house rules. They are non-negotiable. Even if you bring pizza.

## 1. The Philosophical Foundation

We practice **Clean Code** here.
* If your method is longer than my attention span - approx. 10 lines - it will be rejected.
* If you name variables `x`, `temp`, or `data`, a script will automatically format your hard drive.
* **Comments:** Explain the *Why*, not the *How*. The code explains the *How*. If the code does not explain the *How*, the code is bad.

## 2. The XML Tag Fetish - C# Special

I love XML documentation. I demand that you document **EVERYTHING**.
* Public Class? `<summary>`.
* Private Field? `<summary>`.
* An empty constructor? Be creative.

If I hover over a method and do not see a beautifully formatted info box, a kitten cries somewhere. Do you want kittens to cry?

## 3. Test Driven Development - Trust is good, Assert is better

* **No Tests = No Merge.** Simple as that.
* We aim for 100% Code Coverage. Not 99%. Not "I tested the important parts".
* If your test "works but I do not know why", it does not work.
* Mocks are your friends. Do not overdo it, or you mock reality itself.

## 4. The Workflow - The Gauntlet

1.  **Issue first:** Open an issue before starting a PR. Maybe I do not want the feature. Save us both the tears.
2.  **Branch Names:** `feature/cool-stuff` is not a name. `feature/issue-42-add-flux-capacitor` is a name.
3.  **Commits:** Use [Conventional Commits](https://www.conventionalcommits.org/).
    * ✅ `feat: add death star laser`
    * ❌ `fix: stuff`
    * ❌ `wip` - Do not even dare.

## 5. Licensing - AGPLv3

Remember: This is an **AGPLv3** household.
Everything you push here belongs to the community. There is no "My Code", there is only "Our Code". If you include proprietary secrets, the Open Source spirit will haunt you.

## 6. CI/CD & The Robot Overlords

If the build is red, do not ping me.
If the linter fails, do not ping me.
If the tests fail, do not ping me.
Fix it. The robots are always right.

---

### tl;dr
Write clean code, test everything, document obsessively and be nice. Then we can be friends.

Good luck. You will need it.
