#  Shared Passwords

## Wi-Fi Access

| | |
|---|---|
| **Network name (SSID)** | `super gekke bois` |
| **Password** | `hygh2kagWsfi6atg` |

---

## Shared NAS

The NAS is available **only on the local network**.

### Network Addresses

| | |
|---|---|
| **Windows** | `\\SynologyDS\zzs15a` |
| **macOS** | `smb://SynologyDS/zzs15a` |
| **Linux** | `//SynologyDS/zzs15a` |

### Login Credentials

| | |
|---|---|
| **Username** | `guest` |
| **Password** | `E^0t.mw4` |

## Linux NAS Setup

### 1. Install Required Packages

```sh
sudo apt-get update
sudo apt-get install cifs-utils nfs-common
```

### SMB CREDENTIALS FILE

```text
username=guest
password=E^0t.mw4
```
(Save as "smb_credentials")

### PERMISSIONS

```sh
chmod 600 smb_credentials
```

### MOUNT COMMAND

```sh
sudo mount -t cifs //SynologyDS/zzs15a /mnt/nas_smb -o credentials=/path/to/smb_credentials
```

NOTE: NAS IS ONLY AVAILABLE ON THE LOCAL NETWORK

---

## DROPOUT LOGIN

| | |
|---|---|
| **Email** | `feeshunofficial@gmail.com`
| **Password** | `f3.DUt%QU,j=n^A`