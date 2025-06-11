Here's an improved, professional, and visually clean version of your `README.md` for setting up a **FiveM QB-Core** server on a personal computer. It includes clearer instructions, formatting, and better structure for readability:

---

# 🚓 FiveM QB-Core Server – Startup Guide (Local PC Hosting)

## 📄 Official Documentation

Before proceeding, refer to the official FiveM setup docs:
🔗 [FiveM Server Manual](https://docs.fivem.net/docs/server-manual/setting-up-a-server/)

---

## 🧰 Prerequisites

### 1. 📥 Download Required Tools

| Tool                   | Purpose                  | Download Link                                                                        |
| ---------------------- | ------------------------ | ------------------------------------------------------------------------------------ |
| **FiveM Server Files** | Core server setup        | [Click here](https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/) |
| **XAMPP**              | Localhost MySQL & Apache | [Click here](https://www.apachefriends.org/download.html)                            |
| **HeidiSQL**           | GUI for SQL management   | [Click here](https://www.heidisql.com/download.php)                                  |

---

## 🛠️ Installation & Setup Steps

### 2. ✅ Setup Localhost

* Open **XAMPP**.
* Start **Apache** and **MySQL** services.
* Use **HeidiSQL** to manage your SQL databases.

### 3. 🗃️ Extract and Run Server Files

* Extract the downloaded **FiveM server files** into your desired directory.
* Navigate to the folder and **run `FXServer.exe`**.

### 4. 🧩 Server Setup

* Go through the **FXServer registration** steps.
* When prompted, select **QB-Core** as the base framework.

---

## 🌐 Network Configuration

### 5. 🔓 Port Forwarding (for Public Access)

* Open the following ports on your **Wi-Fi router and firewall**:

  * **UDP:** `30120`
  * **TCP:** `30120`
* Ensure your system uses a **static IP address**.
* (Optional but recommended) **Disable firewall** for smoother connection while testing (re-enable when not hosting).

---

## 🎉 You're All Set!

Your FiveM QB-Core server is now ready. Start customizing and enjoy your roleplay server!
Have fun! 😄

---

## 💡 Tips

* Always run `FXServer.exe` as **Administrator**.
* Backup your server config and database regularly.
* Join the QB-Core Discord or forums for support and scripts.

---

Let me know if you'd like this in actual `README.md` file format or with badges/icons!
