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

![center right width:250px](images/echoes_icon.png)
![center left width:700px](images/compass.jfif)

---

![center](images/echoes_site.JPG)

---

[![width:900px center](images/eo_custom_scripts_site.JPG)](https://custom-scripts.sentinel-hub.com/#sentinel-2)

---
# The system architecture

![bg w:480 right](images/img.png)

* A request is sent to process a given ROI with the given processing script. 
* The processing is done remotely, on a Sentinel-Hub server
* The results (GeoTIFF...) are stored on the VM and transfer to the object store
* The GeoTIFF is transferred to the web-service VM (running GeoServer)    

---

<!-- backgroundColor: black -->

![center](images/eo_custom_scripts.gif)

---

<!-- backgroundColor: default -->

# The code used in EO Service  

### The Python modules ([https://github.com/ECHOESProj](https://github.com/ECHOESProj/)):

[![center](https://mermaid.ink/img/pako:eNptj0ELwjAMhf_KyHm7eOzBk_4Cr4UR2qhF24wkFWTsv9uhA0Fzenn5HrzMEDgSOFBDo0PCi2AeHjtfujbEY-JuGParClWN86hB0mT6CyQsm9nklpqEA6my_El8HaGHTJIxxdZlXlEPdqVMHlyTEeXmwZelcXWKreoxJmMBZ1KpB6zGp2cJ2_5mPu-AO-NdaXkBN01PpA)](https://mermaid.live/edit#pako:eNptj0ELwjAMhf_KyHm7eOzBk_4Cr4UR2qhF24wkFWTsv9uhA0Fzenn5HrzMEDgSOFBDo0PCi2AeHjtfujbEY-JuGParClWN86hB0mT6CyQsm9nklpqEA6my_El8HaGHTJIxxdZlXlEPdqVMHlyTEeXmwZelcXWKreoxJmMBZ1KpB6zGp2cJ2_5mPu-AO-NdaXkBN01PpA)

**eo_io:**  w/r to object sore
**eoian:**  search and download the input satellite data
**eo_custom_scripts:** generate results using the Sentinel-Hub API
**eo_processors:** generate results using satellite data in the object store

---

# The code is containerised


![bg w:300 right](images/dockler-vertical-logo-monochromatic.webp)

This makes it easier to deploy

The code can be run on a container service, such as K8



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

