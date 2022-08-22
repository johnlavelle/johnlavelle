---
theme: dark



---

<!-- Global style -->
<style>
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
</style>

# **The ECHOES Earth Observation Service**  <!-- fit -->

---

![center right width:270px](images/echoes_icon.png)

![center left width:650px](images/compass.jfif)




---

![center](images/echoes_site.JPG)

---
# The system architecture
#
![w:480 center](images/img.png)

---

[![width:900px center](images/eo_custom_scripts_site.JPG)](https://custom-scripts.sentinel-hub.com/#sentinel-2)


---

<!-- backgroundColor: black -->

![center](images/eo_custom_scripts.gif)


---

<!-- backgroundColor: default -->

# The code used in EO Service  

### The Python modules:

[![center](https://mermaid.ink/img/pako:eNptj0ELwjAMhf_KyHm7eOzBk_4Cr4UR2qhF24wkFWTsv9uhA0Fzenn5HrzMEDgSOFBDo0PCi2AeHjtfujbEY-JuGParClWN86hB0mT6CyQsm9nklpqEA6my_El8HaGHTJIxxdZlXlEPdqVMHlyTEeXmwZelcXWKreoxJmMBZ1KpB6zGp2cJ2_5mPu-AO-NdaXkBN01PpA)](https://mermaid.live/edit#pako:eNptj0ELwjAMhf_KyHm7eOzBk_4Cr4UR2qhF24wkFWTsv9uhA0Fzenn5HrzMEDgSOFBDo0PCi2AeHjtfujbEY-JuGParClWN86hB0mT6CyQsm9nklpqEA6my_El8HaGHTJIxxdZlXlEPdqVMHlyTEeXmwZelcXWKreoxJmMBZ1KpB6zGp2cJ2_5mPu-AO-NdaXkBN01PpA)

eo_io: w/r to object sore
eoian: search and download the input satellite data
eo_custom_scripts: generate results using the Sentinel-Hub API
eo_processors: generate results using satellite data in the object store

**The GitHub repo: [https://github.com/ECHOESProj](https://github.com/ECHOESProj/)**

---

# The code is containerised

#

![w:360 center ](images/dockler-vertical-logo-monochromatic.webp)


---

# Jupter Lab on the CREODIAS server

[![width:640 center](images/jupyter.JPG)](https://185.52.192.218:8888)


---

<!-- backgroundColor: default -->

# Automation of the servers

#

![center](images/ansible_log.png)

#

[https://github.com/ECHOESProj/eo-playbooks](https://github.com/ECHOESProj/eo-playbooks)

---

<!-- backgroundColor: black -->

![center](images/playbook.gif)

---

<!-- backgroundColor: default -->

# Overview Documentation

https://github.com/ECHOESProj/eo-docs

