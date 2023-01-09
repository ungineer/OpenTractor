# OpenTractor

A completely open-source electronics system for a Combine Harvester.


The goal of this project is to design and develop a combiner harvester with redundant systems using open-source software, resulting in a highly resilient harvester that can withstand component failures.

To achieve this goal, two different components will be used within each system of the harvester, such as using two different models of GPS modules or two different sensors to measure the harvester's speed. This will allow for continued operation even if one component fails, as the backup component will be able to take over. Additionally, using components from different manufacturers will help ensure resilience against supply chain issues.

KiCad, an open-source electronic design automation tool, will be used to design and simulate the electronic circuits for the harvester. LinuxCNC or Machinekit, open-source software, will be used to control the harvester's motion through the creation and execution of motion control programs based on input from sensors and actuators.

We will show John Deere that open-source is the future, no more pay-to-play.

---

### Organization

Each subsystem is in its own directory with a readme.

---

### Contribution

This project is run by volunteers, not experts. If you have skills in a specific area, please create a PR.
