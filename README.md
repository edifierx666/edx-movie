# edx-movie skills

AI 影视创作技能包，每个子文件夹是一个标准 skill（文件夹名 = SKILL.md 里的 name）。

| Skill | 用途 | 来源 |
|---|---|---|
| edx-movie-seedance-prompt-builder | Seedance 2.0 / Higgsfield 电影级单镜头视频提示词（CINEDANCE v4.4.2，英文） | Higgsfield 原创 |
| edx-movie-cinematic-prompt-toolkit | 导演模板库 T01–T22：人物三视图、场景图、分镜、视频提示词、连续性审计（完整版） | 社区 |
| edx-movie-tygg-ai-film-studio | 剧本→分镜→资产→Blender 白模预演→参考视频与 Seedance 提示词（v3.2.7） | 太阳鸽鸽老师原创 |
| edx-movie-film-look-prompts | 电影画面质感底座提示词（ALEXA 35、Kodak 500T、蓝调时刻布光） | 由「画面质感提示词.rtf」整理 |

## 已知问题

edx-movie-tygg-ai-film-studio 原始包不完整：SKILL.md 引用的 33 份参考文档只有 9 份，以下 24 份缺失，另缺 scripts/validate_previs_fast.py 与 scripts/validate_handoff.py。拿到完整原包后放进对应目录即可。

commercial-architecture-blockout.md, contact-hand-ik.md, directing-story-and-editing.md, fast-validation.md, hyper3d-scene-assets.md, interaction-choreography.md, interactive-development.md, offline-handoff-check.md, performance-budget.md, previs-visual-contract.md, production-approval-gates.md, production-document-templates.md, project-documentation.md, reality-to-design-quality.md, reference-image-driven-assets.md, reference-prompt-template.md, reference-video-delivery.md, research-evidence-and-reality.md, research-sources.md, revision-and-handoff.md, scene-blockout-and-camera-motion.md, scene-contract.md, scene-semantic-detail-library.md, user-review-and-prompt-handoff.md
