# 🎫 osTicket Post Installation Configuration

## ✅ Post Installation Steps for osTicket

Once osTicket is installed, follow these steps to complete the configuration and ensure that the system runs optimally. 🚀

---

## 1. 🔐 Set File Permissions

### 🪟 **Windows:**

To ensure that the osTicket application can write to the necessary directories, you need to set the proper file permissions for the following folders:

- `C:\inetpub\wwwroot\osTicket\include`
- `C:\inetpub\wwwroot\osTicket\attachments`
- `C:\inetpub\wwwroot\osTicket\files`

🛠️ **Steps**:
- Right-click the folder.
- Go to **Properties** → **Security** tab.
- Grant **Read/Write** permissions to the **IIS_IUSRS** group.

### 🐧 **Linux:**

Use the following commands in your terminal:

```bash
chmod -R 777 /var/www/osticket/include
chmod -R 777 /var/www/osticket/attachments
chmod -R 777 /var/www/osticket/files

