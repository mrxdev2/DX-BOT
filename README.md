# DX-BOT 🚀

High performance multi-device WhatsApp bot built with Node.js.

---

## 🛠️ Hatua ya Kwanza: Pata Session ID
Kabla ya kubonyeza kitufe cha kudeploy, unahitaji kupata **Session ID** kwa ajili ya kuunganisha bot na WhatsApp yako.
* Bonyeza link hii kupata Session ID: [Mega Pairing Site](https://mega-pairing.onrender.com/)
* Weka namba yako ya WhatsApp yenye nambari ya utambulisho wa nchi (mfano: `2557XXXXXXXX`).
* Utapewa kodi ya tarakimu 8 (Pairing Code) kwenye simu yako. Iingize kwenye WhatsApp -> Linked Devices.
* Baada ya hapo, utatumiwa ujumbe wenye **Session ID** kwenye chat yako ya WhatsApp. Copy hiyo ID.

---

## 🚀 Deploy to Heroku

Bonyeza kitufe kilicho chini ili kuanza kurusha bot yako Heroku moja kwa moja:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/mrxdev2/DX-BOT)

---

## ⚙️ Mipangilio Muhimu (Environment Variables)

Unapobonyeza kitufe cha Deploy, Heroku itakuomba ujaze vitu vifuatavyo:

| Jina la Sehemu (Key) | Maelezo |
| :--- | :--- |
| **`SESSION_ID`** | Weka ile kodi uliyomfuta kwenye hatua ya kwanza (Lazima). |
| **`OWNER_NUMBER`** | Namba yako kuu ya WhatsApp (mfano: `2557XXXXXXXX`). |
| **`MONGO_URL`** | Link yako ya MongoDB kwa ajili ya kutunza data (Inashauriwa). |
| **`BOT_NAME`** | Jina unalotaka bot yako iwe nalo (Mfano: `DX-BOT`). |
| **`PREFIXES`** | Alama ya kuanzia amri za bot (Mfano: `.`, `!`, `/`). |

---

## 📝 Leseni
Project hii ipo chini ya leseni ya MIT. Angalia faili la `LICENSE` kwa maelezo zaidi.
