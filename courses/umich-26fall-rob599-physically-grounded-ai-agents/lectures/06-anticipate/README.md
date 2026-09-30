# Debate 4 · Anticipate

ROB 599 · Lecture 6 · Oct 7, 2026.

Debate 3 compared two ways to learn what an image shows: predict every pixel (diffusion) or predict an embedding (JEPA). This one takes both to the next stage of the loop, [anticipate](https://github.com/yayuanli-org/awesome-physical-ai/tree/main/courses/umich-26fall-rob599-physically-grounded-ai-agents/lectures/02-where-the-field-stands#23-anticipate-think-before-you-move): predict what the world does next, then act on the prediction with a robot arm.

| paper | why |
|---|---|
| VLA-JEPA. Sun et al., ECCV 2026. [arXiv](https://arxiv.org/abs/2602.10098) · [project](https://ginwind.github.io/VLA-JEPA/) · [code](https://github.com/ginwind/VLA-JEPA) | JEPA on a robot. It anticipates by predicting the embeddings of the next frames, never their pixels, and learns its actions from that. |
| Cosmos Policy. Kim et al., ICLR 2026. [arXiv](https://arxiv.org/abs/2601.16163) · [project](https://research.nvidia.com/labs/dir/cosmos-policy/) · [code](https://github.com/NVlabs/cosmos-policy) | Diffusion on a robot. A video diffusion model imagines the next frames and, in the same pass, generates the actions and a guess at how well they will end. |

Prepare the five PACES rows for both.
