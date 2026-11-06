<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=225&color=0:050505,50:1155B5,100:1F6FEB&text=GSAM%20Robotics&fontSize=65&fontColor=ffffff&animation=fadeIn&fontAlignY=35" alt="Samuel Campelo"/>

**Open-source robotics from the students of Instituto Federal de Educação, Ciência e Tecnologia da Bahia (IFBA) – Campus Salvador**

*Code, knowledge and lessons learned from the teams of the Automation and Mechatronics Systems Research Group (GSAM).*

</div>

---

## 👋 About us

**GSAM-Robotics** is the home of the source code produced by the robotics teams that have competed under the **GSAM – Grupo de Pesquisa em Sistemas de Automação e Mecatrônica** (Automation and Mechatronics Systems Research Group) at the **Instituto Federal de Educação, Ciência e Tecnologia da Bahia (IFBA) – Campus Salvador**.

This organization exists to:

- 📦 **Preserve** the code of every team that has competed in robotics events through GSAM.
- 🤝 **Share** knowledge between current and future IFBA students, so no team has to start from zero.
- 🌍 **Encourage open source** in robotics education, inside and outside our campus.

## 🤖 What you will find here

Repositories in this organization contain the software behind our robots, such as:

- 👁️ Computer vision: OpenCV pipelines for line detection, color masks (black, green and red), contour analysis, region-of-interest experiments and lighting compensation with CLAHE
- 🎛️ PID control: line-following controllers that turn sensor or camera error into differential motor speeds, plus notes on tuning
- 🧭 Track interpretation and navigation logic: intersections with green markings, 180° turns, line gaps, lost-line recovery, obstacle avoidance and finish-line detection
- 📐 Odometry: differential-drive pose estimation (x, y, θ) from wheel rotation, and comparisons with time-calibrated movements
- 🔌 Sensors and hardware integration: infrared line sensors, RGB/color sensors, distance sensors and motor control on Raspberry Pi through Open-RDK
- 🧵 Embedded software patterns: threaded motor command drivers and robot control loops written in Python
- 🖥️ Debug tools: browser-based dashboards with live camera streams, detection overlays and real-time telemetry (Flask)
- 🧪 Testing and calibration: scripts to test vision and hardware communication in isolation, and notes from physical testing on the robot
- 📝 Documentation: architecture overviews, hardware notes, lessons learned and competition strategy decisions


Our teams take part in robotics competitions such as the **OBR** (Olimpíada Brasileira de Robótica), **FTC** (FIRST Tech Challenge), **MNR** (Mostra Nacional de Robótica) and Robodori, among others.

## 🗂️ Repository organization

To keep things easy to find, we recommend naming repositories as:

```
<COMPETITION>-<Team>
```

For example: `OBR-XTeam`, `FTC-YTeam`.

Each repository should include, at minimum:

| Item | Purpose |
|------|---------|
| `README.md` | What the project is, how to build/run it, and which competition it was made for |
| `LICENSE` | So others know how they can reuse the code |
| Hardware notes | Boards, sensors, motors and wiring used |
| Lessons learned | What worked, what didn't, and what you would do differently |

## 🚀 How to contribute

We welcome contributions from IFBA students, alumni, mentors and the wider robotics community.

1. **Explore** the repositories and find something you'd like to improve or learn from.
2. **Open an issue** to report a bug, ask a question or suggest an idea.
3. **Fork** the repository, create a branch and make your changes.
4. **Submit a pull request** describing what you changed and why.

Are you part of a GSAM team and want to publish your code here? Get in touch with the organization maintainers to be added as a member and create your team's repository.

## 📚 Why open source?

Robotics competitions are a great place to learn, but a lot of knowledge is lost when a team graduates. By keeping our code open and documented, we aim to:

- Shorten the learning curve for new members
- Build on each other's work year after year
- Show that school projects can be real, reusable engineering
- Give back to the community that shares knowledge with us

## 📄 Licensing

Each repository defines its own license. When in doubt, check the `LICENSE` file in the repository before reusing the code, and please give credit to the original teams.

## 🔗 Links

- 🏫 **IFBA – Campus Salvador:** [salvador.ifba.edu.br](https://portal.ifba.edu.br/salvador)
- 💻 **Organization:** [github.com/GSAM-Robotics](https://github.com/GSAM-Robotics)

---

<div align="center">

*Built by students, for students. Fork it, learn from it, make it better.* 🛠️

</div>
