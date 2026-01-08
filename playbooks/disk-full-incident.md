# 💽 Disk Full Incident Playbook

## 🚨 Scenario
Production server disk reaches 95–100% usage.

---

## 🔍 Detection
- Monitoring alert triggered
- Backup or application failures

---

## 🧠 Diagnosis Steps
1. Identify largest directories
2. Check logs and backup folders
3. Validate retention policies
4. Detect runaway processes

---

## 🛠️ Immediate Actions
- Remove old logs
- Compress backup files
- Move data to secondary storage

---

## 🔁 Recovery
- Restore disk to safe threshold (<80%)
- Resume failed services

---

## 🧪 Post-Incident
- Implement automated cleanup
- Add disk usage alerts
