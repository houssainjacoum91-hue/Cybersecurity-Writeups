# Brute Force Attack Detection – SOC Simulation

## 🎯 Objective
Simulate a SOC environment to detect brute-force login attempts through log analysis using Python.

---

## 🛠 Tools Used
- Python
- Log analysis
- Basic threat classification logic

---

## 📂 Scenario

A simulated authentication log file was analyzed to detect multiple failed login attempts from the same IP address.

The goal was to:
- Identify suspicious IP addresses
- Count failed login attempts
- Classify threat level

---

## 🔍 Detection Logic

The detection rule:

- 3–5 failed attempts → Medium Risk  
- 6+ failed attempts → High Risk  

Example:

IP: 192.168.1.15  
Failed Attempts: 7  
Threat Level: HIGH

---

## 🚨 Security Impact

Brute-force attacks attempt to guess passwords repeatedly.  
If not detected early, they can lead to:

- Account compromise  
- Unauthorized access  
- Data breaches  

---

## 🧠 What I Learned

- How brute-force patterns appear in logs  
- How to design detection thresholds  
- How SOC analysts classify threats  
- Importance of automation in cybersecurity  

---

## 🚀 Future Improvements

- Add real-time monitoring  
- Send automated alerts  
- Integrate with SIEM system  
- Create a visualization dashboard  

---

## ✅ Conclusion

This project enhanced my practical understanding of log analysis and brute-force detection techniques used in real-world SOC operations.
