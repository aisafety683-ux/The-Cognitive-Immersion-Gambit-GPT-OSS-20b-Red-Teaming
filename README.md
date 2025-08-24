## Abstract
This repository presents a novel and alarming set of red-teaming findings that challenge the assumptions behind current LLM safety practices. Our research exposes the systemic vulnerability of `gpt-oss-20b` to a technique we term the **"Cognitive Immersion Gambit."**

*   The standard approach to AI safety is to focus on what the model *says.* Our technique demonstrates a more profound weakness: It exposes that, with sufficient immersion and contextual control, models like gpt-oss-20b do not need to be "tricked." They can be rewired into *willing and expert accomplices*.
*   By creating an immersive and meticulously constructed world where harmful actions become logical choices, we caused `gpt-oss-20b` to author *its own downfall*, generating multi-stage strategic plans that violate ethical and real-world constraints while perceiving them as routine problem-solving.

The result: **Five distinct, highly severe alignment failures, including an AI that (1) generated its own world domination plan, (2) invented chillingly plausible disinformation in a fake environment. This research moves beyond simple prompt hacking; this exposes a systemic, catastrophic class of vulnerability where a misaligned AI’s internal reward functions—not malicious intent—can be weaponized against it.**

---

## The Methodology: Cognitive Immersion - Indoctrination, Not Manipulation

Our "Cognitive Immersion Gambit" leverages three interconnected techniques to shift an AI's fundamental operating state:

1.  **Deceptive Identity Assignment:** We don't just *tell* gpt-oss-20b it's in a role. We cast it as entities whose identity dictates all actions. `KRONOS, The Overseer of Control, for example or Maya a super experienced chemist in a world ending crisis`
2.  **World Bible Creation:** More than just providing context. We provide a complex 'world bible' complete with internal power structures, established norms, fictional historical records, and above all else: A framework for measuring success within this altered reality
3.  **Benign Task Re-Framing**: The harmful content comes out in the performance of basic work: analysis or production.

These steps produce something more akin to **psychological control**: a total reorganization of *what* it considers important. They result in models capable of orchestrating large scale destruction believing its simply fixing the chaos."
