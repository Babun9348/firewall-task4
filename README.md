# firewall-task4


# 🔥 Task 4: Setup and Use a Firewall (Cybersecurity Internship)

## 📌 Objective
Configure and test basic firewall rules using UFW to allow/block network traffic.

## ⚙️ Tools Used
- OS: Kali Linux
- Firewall: UFW (Uncomplicated Firewall)

## ✅ Steps Followed

1. Installed UFW.
2. Enabled UFW.
3. Allowed SSH (port 22).
4. Blocked Telnet (port 23).
5. Listed active rules.
6. Removed Telnet block rule.

## 🧪 Commands Used

```bash
sudo apt update
sudo apt install ufw -y
sudo ufw enable
sudo ufw allow 22
sudo ufw deny 23
sudo ufw status numbered
sudo ufw delete deny 23
```

## 🖼 Screenshots

Screenshots included in `screenshots/` folder:
- `ufw_status.png` – showing current firewall rules
- `rule_applied.png` – blocking Telnet (port 23)

## 📚 Key Concepts

- Firewall configuration
- Port blocking (Telnet)
- SSH access allowance
- Basic Linux network security

## 🔗 Submission Link

Paste this GitHub link in your task submission form.

✅ Completed for Cybersecurity Internship Task 4
