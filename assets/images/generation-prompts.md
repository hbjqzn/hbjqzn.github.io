# README 视觉素材生成提示词

两张配图均使用内置 image_gen 工具生成，作为团队宣传页面的概念插画。

## 团队主视觉

输出文件：`team-hero.png`

```text
Use case: ads-marketing
Asset type: wide hero banner for a Chinese machine intelligence research team's GitHub README.
Primary request: a polished research-team promotional illustration, tying humanoid robotics, autonomous driving, solar photovoltaic forecasting, and large language model agents into one coherent future-facing landscape.
Style/medium: sophisticated editorial 3D illustration with precise forms, soft atmospheric depth and restrained luminous technical linework; professional academic identity.
Composition/framing: panoramic 2:1 banner. Strong readable Chinese headline in generous dark negative space across the upper left. Below and toward the right, a white and graphite humanoid robot in three-quarter view, an unbranded autonomous car with subtle sensor rays following a curved road, a small solar panel field with an abstract forecast curve without axis numbers, and a luminous network of tool and agent nodes. The scenes should flow together rather than look like unrelated pasted photos. Include a subtle orange citrus fruit and leaf as a visual echo of the provided slogan, not a separate logo. Use comfortable safe margins.
Lighting/mood: calm, confident, exploratory. Deep midnight navy background, cyan data accents, warm orange citrus highlights, clean white robotics.
Text (verbatim): large headline "橘生淮北则为智"; smaller title "淮北机器智能研究团队".
Typography: crisp, legible Chinese sans serif, exact characters, strong contrast; headline remains readable at README width.
Constraints: concept illustration, no real team member portraits; only the two specified text strings; no fake achievements, numeric statistics, logos, brand marks or watermarks; avoid visual clutter and tiny interface labels.
```

## 四大研究方向

输出文件：`research-overview.png`

```text
Use case: ads-marketing
Asset type: research directions overview illustration for a Chinese machine intelligence team's GitHub README.
Primary request: one polished landscape image showing four research themes in a clean 2 by 2 grid of equal illustrated panels, each with a single prominent Chinese title.
Style/medium: premium editorial 3D scientific concept illustration. Unified midnight navy, graphite, white, cyan and restrained citrus orange accents; clean cinematic depth, precise objects and modest technical overlays.
Composition/framing: 3:2 landscape format with generous outside margins and clear consistent gutters. Each panel has large legible Chinese title across its top and an immediately understandable scene underneath. No central badge or decorative title competing with the panels.
Top left panel: a white and graphite humanoid robot with complete natural articulated hands carrying out a tabletop manipulation task in a modern robotics laboratory, subtle joint and vision cues. Title exactly "人形机".
Top right panel: an unbranded autonomous car on an urban road, cyan sensing arcs, translucent detection boxes around road users and a clear planned route staying on the road. Title exactly "自动驾驶".
Bottom left panel: a solar photovoltaic array under changing sunshine and clouds, with a clean conceptual power forecast line in a translucent inset; no numbers or claimed accuracy. Title exactly "光伏发电功率预测".
Bottom right panel: a luminous central AI node connected to several distinct agent nodes and icons for search, documents, code tools and task planning, visually readable cooperative tool use. Title exactly "大模型智能体".
Text (verbatim): "人形机", "自动驾驶", "光伏发电功率预测", "大模型智能体".
Typography: consistent large crisp Chinese sans serif, exact characters, high contrast, all four titles equally readable at typical README width.
Constraints: only those four text strings; no tiny illegible interface text, extra text, logos, real brands, statistics, watermarks, ranking or achievement claims; conceptual research scenes rather than claimed team photographs.
```

## 名称与术语更新

以下为本次使用内置 image_gen 工具编辑图片的实际提示词，分别更新团队名称和人形机标题。

### 主视觉文字编辑

```text
Use case: text-localization
Asset type: Chinese research team GitHub README hero banner.
Input image: the supplied local image is the edit target.
Primary request: change only the smaller subtitle beneath the large slogan to the exact text "淮北机器智能研究团队".
Typography: match the existing pale cyan-white Chinese sans-serif lettering and centered subtitle alignment, balanced letter spacing, fitting between or around the horizontal decorative lines. All 10 characters must be rendered correctly and legibly. Adjust only this subtitle's font size or decorative line lengths if needed to fit.
Invariants: keep the large headline "橘生淮北则为智" exactly as it is. Preserve the humanoid holding an orange, autonomous vehicle and road, solar panels and forecast lines, AI tool network, all scenery, colors, lighting, and the panoramic 2:1 composition. Preserve image dimensions and all areas outside the subtitle as closely as possible.
Constraints: no new copy, no extra text or logos, no watermark. Only the team subtitle changes.
```

### 研究方向文字编辑

```text
Use case: text-localization
Asset type: four research directions overview for the Chinese team "淮北机器智能研究团队".
Input image: the supplied local image is the edit target.
Primary request: change only the upper-left panel's Chinese title to the exact text "人形机".
Typography: use the same bold white Chinese sans-serif style, font height, upper-left alignment and safe margins as the current title. Render exactly these three characters: 人 形 机. Do not add any other characters.
Invariants: preserve the humanoid manipulation scene beneath the title and all four panel artwork, borders, gutters, objects, colors, lighting, textures and composition. Preserve the other three titles exactly: "自动驾驶", "光伏发电功率预测", "大模型智能体". Keep the original 1536 x 1024 landscape dimensions.
Constraints: edit only the top-left text area; no new text, no extra logos or watermark; do not regenerate the four scenes or change any other title.
```
