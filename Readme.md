# smartbulb-lab
# IoT Security Lab: Smart Bulb Vulnerability Analysis
A hands-on laboratory for learning IoT security concepts through a simulated smart bulb device.
Source from: https://github.com/mitayag/iotsecurity/tree/main

## 📝 Overview
This laboratory provides a safe, controlled environment for students to learn about IoT security by analyzing and testing a simulated smart bulb. Students will perform various security tests and understand common IoT vulnerabilities.

## 🎯 Learning Objectives
- Understand basic IoT device functionality
- Identify common security vulnerabilities in IoT devices
- Execute and analyze basic security tests
- Learn about real-time attack impacts
- Develop basic security testing skills

## 🛠️ Prerequisites
- Python 3.x installed
- Basic understanding of command line
- Text editor (VSCode, Notepad++, etc.)
- Web browser (Chrome/Firefox recommended)

## 📦 Required Packages
```bash
pip install flask flask-socketio
```

## 🚀 Quick Start
1. Clone the repository
```bash
git clone [repository-url]
cd smartbulb-lab
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Start the simulator
```bash
python app.py
```

4. Access the interface
```
http://localhost:8080
```

## 📁 Project Structure
```
smartbulb/
│
├── smart_bulb_server.py                 # Main server application
├── templates/
   └── index.html        # Web interface

```

## 💻 Features
- Real-time web interface
- Multiple attack scenarios
- Interactive controls
- Visual feedback
- Debug console
- Attack detection alerts

## 🎮 Available Attacks
1. Basic Attacks
   - Power control
   - Brightness manipulation
   - Color changes

2. Advanced Attacks
   - DoS simulation
   - State manipulation
   - Fuzzing tests

## 📝 Laboratory Tasks
1. Basic Device Analysis
   - Access interface
   - Test controls
   - Document features

2. Security Testing
   - Execute basic attacks
   - Monitor responses
   - Record results

3. Advanced Analysis
   - Create custom attacks
   - Analyze vulnerabilities
   - Suggest improvements

## 📋 Requirements Checklist
- [ ] Python 3.x installed
- [ ] Flask and Flask-SocketIO installed
- [ ] Web browser
- [ ] Command Prompt/PowerShell access
- [ ] Text editor
- [ ] Network access

## ⚠️ Important Notes
1. Safety Guidelines
   - Educational purpose only
   - No real device testing
   - Follow instructor guidance
   - Report issues immediately

2. Common Issues
   - Port conflicts (8080)
   - Python dependency errors
   - Command syntax errors
   - WebSocket connection issues

## 🔧 Troubleshooting
1. Port in Use
```bash
netstat -ano | findstr :8080
taskkill /PID <PID> /F
```

2. Package Issues
```bash
pip install --force-reinstall flask flask-socketio
```

## 📚 Additional Resources
- [OWASP IoT Top 10](https://owasp.org/www-project-internet-of-things/))
- [IoT Security Foundation](https://www.iotsecurityfoundation.org/)
- [NIST IoT ](https://www.nist.gov/internet-things-iot)
- [ETSI EN 303 645(Cyber Security for Consumer Internet of Things: Baseline Requirements)](https://www.etsi.org/deliver/etsi_en/303600_303699/303645/03.01.03_60/en_303645v030103p.pdf)


## 📝 Documentation
Students should maintain:
1. Attack logs
2. Test results
3. Security findings
4. Improvement suggestions

## 👥 Support
- Report issues through the issue tracker
- Contact course instructor for assistance
- Check troubleshooting guide

## ✍️ Authors
Ching-Huang Lin

## 📜 License
This project is licensed for educational purposes only.

## 🤝 Contributing
1. Fork the project
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open pull request

## 🔄 Version History
- v1.0.0 - Initial release
  - Basic functionality
  - Core attacks
  - Documentation

## 🙏 Acknowledgments
- IoT Security Community
- Educational Contributors
- Testing Team

## 📞 Contact
gbox@ntut.edu.tw

---
*Note: This laboratory is designed for educational purposes only. Do not apply these techniques to real devices without proper authorization.*

