# Analyse Engineering — Traffic Computer Vision

## Accomplishment inventory

**Provisional period:** December 2020–March 2021. **Role context:** software engineering and technical leadership during an early-career engagement.

Refreshed October 27, 2026 from the existing career inventory. Earlier resume materials and a publication reference support this history; this refresh did not independently inspect deployment records, evaluation logs or the full paper.

## Scope and attribution

Built traffic-counting and vehicle-classification software for roadway video under day/night, low-light and non-ideal-camera constraints.

- **Individual implementation:** initial desktop interface.
- **Technical leadership:** model evaluation, dataset work, tracking research and mentoring.
- **Team outcomes:** integrated software and reported deployment.

Leadership means technical direction and mentorship; it does not establish formal management of direct reports or sole implementation of the team's work. The precise employer/engagement naming requires confirmation.

## Computer-vision engineering

| Contribution | Methods / skills | Supported outcome |
|---|---|---|
| Directed detector/classifier evaluation | YOLO-family models, CNN-based detectors, Detectron and RetinaNet | Compared approaches for roadway traffic and application constraints |
| Guided dataset annotation | Domain-specific vehicle classes; day/night imagery | Built data suited to the target traffic conditions |
| Researched low-light preprocessing | Frame enhancement and image-processing experiments | Addressed non-ideal lighting |
| Worked on multi-object tracking | DeepSORT and SORT | Addressed occlusion and fast-moving vehicles |
| Guided integration | Detection, classification, tracking and counting | Contributed to an end-to-end application rather than an isolated model notebook |
| Balanced processing cost and quality | Model/runtime comparison and video-processing experiments | Evaluated practical application trade-offs without asserting an unverified benchmark |

Python, PyTorch, TensorFlow and Keras appear in the historical technology inventory. Exact model versions should not be assigned to the engagement without checking dated artifacts.

## Application engineering and technical leadership

- Built the initial operator interface using Tkinter.
- Mentored the later Kivy interface work.
- Coordinated technical work across annotation, preprocessing, model experiments, tracking and frontend development.
- Mentored engineering and research interns.
- Earlier materials describe software deployment at multiple sites; an independently verified acceptance record is not established.

## Publication

Existing career materials record co-authorship of:

**“Real-time Vehicle Detection, Classification & Tracing Using State-Of-The-Art Dataset” — IEEE INCET, 2022.**

The publication reference supports the research topic; it does not independently prove every personal contribution, deployment claim or metric in earlier resumes. Do not attribute later Microsoft research to this engagement.

## Separate concurrent engagement

**Skillzera, December 2020–March 2021:** community and technical coordination involving web, Android and custom-software projects, intern programs, coding education and hackathons.

Keep this separate from Analyse Engineering. Its team, community, project and award claims must not be merged into the traffic-software work.

## Verification caveats

- **Dates:** earlier materials disagree on the start month; the provisional range above is not a resolution.
- **Title:** internship, software-development and technical-lead descriptions vary. Confirm the formal designation before publishing one.
- **Metrics:** reported accuracy, dataset size, processing time, vehicle-class count and team size are not consistently defined or corroborated. They are withheld rather than combined into a stronger claim.
- **Evaluation:** do not relabel an undefined accuracy figure as mAP, F1, precision, recall or per-class performance.
- **Models:** model families and versions vary across materials. Use broad supported descriptions until dated implementation records are checked.
- **Recognition:** award attribution differs between separate early ventures; do not attach an unresolved award to this role.

## Reuse guidance

Strongest grounded themes: applied computer vision, dataset development, low-light preprocessing, object tracking, Python desktop productization and technical mentorship. Keep individual and team ownership separate. Publication metadata, formal role details and quantitative claims should be checked before external reuse; do not invent replacement metrics.
