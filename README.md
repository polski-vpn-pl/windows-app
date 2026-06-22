<div align="center">

# 🇵🇱 Polski VPN — Windows

**Prosty, szybki klient VPN dla Windows 10/11 — z obsługą protokołów OpenVPN i SoftEther.**

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20(x64)-0078D6?logo=windows&logoColor=white)
![Protocols](https://img.shields.io/badge/VPN-OpenVPN%20%2B%20SoftEther-blue)
![Version](https://img.shields.io/badge/version-1.4.0-success)

<a href="../../releases/latest">
  <img alt="Pobierz instalator"
       src="https://img.shields.io/badge/⬇%20Pobierz-instalator%20.exe-0078D6?style=for-the-badge">
</a>

</div>

---

## ✨ W skrócie

**Polski VPN dla Windows** to desktopowy klient VPN dla Windows 10/11. Łączy się z serwerami usługi <a href="https://polski-vpn.pl/">*Polski-VPN.pl*</a> przy użyciu jednego z dwóch protokołów: **OpenVPN** lub **SoftEther VPN** (TCP over HTTPS/TLS). Interfejs jest w języku polskim i minimalistyczny — wybierz serwer, wpisz dane dostępowe które otrzymałeś po zakupie usługi i połącz się. Aplikacja chowa się do zasobnika systemowego i może uruchamiać się przy starcie Windows.


---

## 👤 Dla kogo

| Odbiorca | Dlaczego |
|---|---|
| 🧑‍💻 Użytkownicy usługi **Polski VPN** | Dedykowany, lekki klient serwerów Polski VPN |
| 🖥️ Użytkownicy **Windows 10/11** | Natywna aplikacja desktopowa |
| 🔒 Szukający alternatywy dla OpenVPN | Klient SoftEether na Windows |
| 🛡️ Omijający blokady VPN | SoftEther over HTTPS/TLS |

---

## 🚀 Funkcje

| Funkcja | Opis | Status |
|---|---|:---:|
| Dwa protokoły VPN | OpenVPN, SoftEther | ✅ |
| Protokół SSTP | Wbudowany RAS Windows | 🚧 planowane |
| Wybór protokołu | Przełącznik w ustawieniach | ✅ |
| Lista serwerów | Wybór z poziomu aplikacji | ✅ |
| Auto-reconnect | Ponawianie przy zerwaniu sesji | ✅ |
| Limit prób | Konfigurowalny | ✅ |
| Zasobnik systemowy | Chowanie do traya, menu (połącz/rozłącz), status | ✅ |
| Autostart | Uruchamianie przy starcie Windows | ✅ |
| Start zminimalizowany | Uruchom schowany do zasobnika | ✅ |
| Pełny tunel | Cały ruch (`0.0.0.0/0`) jest tunelowany przez VPN | ✅ |

---

## 🔌 Protokoły — co dokładnie działa

| Cecha | OpenVPN | SoftEther |
|---|:---:|:---:|
| Transport | UDP / TCP | TCP (HTTPS/TLS) |
| Silnik na Windows | oficjalny `openvpn.exe` | oficjalny **SoftEther VPN Client** |
| Sterownik | TAP | wirtualny adapter SoftEether |
| Szyfrowanie | AES-256-GCM / AES-128-* | TLS 1.2 (AES) |
| Uwierzytelnianie | login/hasło | login/hasło |
| Statystyki RX/TX | ✅ | 🚧 |


---

## 📥 Instalacja (skrócona)

1. Pobierz **`PolskiVPN-Setup-1.3.0.exe`** z zakładki [Releases](../../releases/latest).
2. Uruchom instalator. Zainstaluje aplikację oraz — w razie potrzeby — **OpenVPN** i **SoftEther VPN Client** wraz ze sterownikiem adaptera (jeden klik).
   > Niepodpisany instalator: jeśli SmartScreen ostrzeże — *Więcej informacji → Uruchom mimo to*.
3. Uruchom **Polski VPN** (Menu Start). Przy starcie kliknij **Tak** w oknie UAC — VPN wymaga uprawnień administratora.
4. W aplikacji: wybierz **protokół** i **serwer**, wpisz **login i hasło** otrzymane po zakupie usługi, kliknij **POŁĄCZ**.

To wszystko. Aplikację możesz schować do zasobnika (zamknięcie okna) i ustawić autostart w *Ustawieniach*.

---

## 🖥️ Wymagania

| Element | Wymaganie |
|---|---|
| System | Windows 10 (1809+) lub Windows 11 |
| Architektura | x64 |
| Uprawnienia | Administrator (instalacja sterowników, tworzenie adaptera, routing) |
| Sieć | Dostęp do internetu + aktywne konto na [polski-vpn.pl](https://polski-vpn.pl/) |

---


## 📜 Licencje

- Kod aplikacji - własność dostawcy usługi **Polski-VPN.pl**.
- **OpenVPN** - GPLv2.
- **SoftEther VPN** - Apache License 2.0.

Komponenty zewnętrzne są bundlowane jako **oficjalne, niemodyfikowane** instalatory i uruchamiane jako osobne procesy.

---

<div align="center">
<sub>Zbudowane dla użytkowników Polski-VPN.pl</sub>
</div>
