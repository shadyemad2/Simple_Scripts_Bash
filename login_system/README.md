# 🔐 Bash User Authentication System

A simple **Bash script** that handles user login and registration with a CSV file as the backend.

## 📜 Features

- [x] User Login  
- [x] User Registration with password confirmation  
- [x] Password masking (hidden input)  
- [x] Duplicate email check  
- [x] Menu-driven interface  
- [x] Show total number of registered users

## 📁 Files

- `users.csv`: Stores registered users in `email,password` format.  
- `auth.sh`: Main Bash script.

## 🚀 How to Use

### 1. Make the script executable
```bash
chmod +x auth.sh
```

### 2. Run the script
```bash
./auth.sh
```

### 3. Main Menu Options

- **1)** Login  
- **2)** Register  
- **3)** Exit  
- **4)** Show number of registered users

## 🔒 Example User Entry in `users.csv`

```
user@example.com,mysecurepassword
```

> ⚠️ Passwords are stored in plain text in this version.  
> You can improve security by hashing passwords using `sha256sum`.
## 💡 Future Enhancements

- [ ] Password hashing  
- [ ] Password reset  
- [ ] Account deletion  
- [ ] Email validation  
- [ ] Login attempt limits

## 📌 Author

**Shady Emad**  
🔗 [GitHub](https://github.com/shadyemad2)

---

📁 Feel free to clone or fork this repo to improve or customize the script!
