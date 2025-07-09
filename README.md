#  Distributed SDN in HAMNET

This project (done during the M.Sc.) explores the feasibility of deploying **distributed SDN architectures** over **HAMNET** (Highspeed Amateur Radio Multimedia Network) using IP routing protocols like **OSPF**. It compares centralized and distributed SDN setups in terms of resilience, scalability, and routing performance.

---

##  Overview

- **Institution**: TU Ilmenau  
- **Author**: Mamdouh Muhammad  
- **Supervision**: M.Sc. Matthias Aumüller  
- **Topic**: Distributed SDN over Wide Wireless Area Networks (WWAN)

---

##  Implementation

- **Tools**:  
  - Mininet for emulation  
  - Ryu SDN controllers  
  - RouteFlow + Quagga for routing  
- **Setup**:  
  - 80 hosts, 21 OpenFlow switches  
  - 2 Ryu controllers with domain separation  
  - Traffic rerouted via OSPF upon link failure  

> See `Topology.py` for full simulation code.

---

##  Results

- Distributed SDN enables fast failover and better load distribution  
- RouteFlow correctly maps IP routes into OpenFlow rules  
- Resilient under link failure and scalable to multi-domain topologies

---

##  Files

- `BRP Paper.pdf` – Brief technical report  
- `BRP Presentation.pptx` – Presentation slides  
- `Topology.py` – Custom Mininet topology script

---

##  References

- [Mininet](http://mininet.org/)  
- [RouteFlow](https://routeflow.github.io/RouteFlow/)  
- [Ryu Controller](https://osrg.github.io/ryu/)

---

Contact: **mamdouh.eac@gmail.com**
