# ❌ SQL Backup Failure Playbook

## 🚨 Scenario
Scheduled SQL Server backups are failing during nightly execution.

---

## 🔍 Detection
- Backup job reports failure
- Missing `.bak` or `.zip` files
- Alert received via Telegram or email

---

## 🧠 Diagnosis Steps
1. Check disk space availability
2. Validate SQL Agent job status
3. Review backup logs
4. Verify network/NAS availability
5. Check file permissions

---

## 🛠️ Immediate Actions
- Free disk space if needed
- Restart failed SQL job
- Validate last successful backup
- Notify stakeholders if SLA is impacted

---

## 🔁 Recovery
- Re-run backup manually
- Validate backup integrity
- Upload to NAS or offsite storage

---

## 🧪 Post-Incident
- Identify root cause
- Improve alerting
- Automate preventive checks
