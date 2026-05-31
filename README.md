# Outevia - Document Image Viewer 

![Outevia Logo](https://outevia.com/assets/logo.png)

Outevia is a Windows application designed to optimize visual analysis inside documents and email messages. It acts as an intelligent visualization layer you use while reading text documents, PDFs, or handling emails, allowing you to instantly isolate and enlarge any selectable image without changing the document layout or zoom, so you can keep your focus on what you are reading.

---


# Outevia – README
 
Outevia is a Windows tool designed to quickly zoom, inspect and annotate images, charts and visual details inside documents and email messages without changing the document zoom level or breaking your reading flow.

---

## 1. System requirements

Check that your PC meets the minimum requirements before installing the application.

- **Operating system:** Windows 10 (1903+) or Windows 11  
- **Runtime:** .NET 6.0 or later – [Download from Microsoft](https://dotnet.microsoft.com/en-us/download)  
- **RAM:** Minimum 4 GB (8 GB recommended)  
- **Disk space:** 120 MB of free space  
- **GPU:** Any GPU with DirectX 11 support  

---

## 2. Installation and startup

Install Outevia and quickly recognize the application startup screen.

1. Download `OuteviaSetup.exe` from the [download page](https://outevia.com/download.php).  
2. Run the setup with administrator privileges.  
3. Follow the guided installation procedure until completion.  
4. At the end of setup, Outevia is added to the Start menu and can remain active in the background.  
5. From **Settings** you can choose whether to launch Outevia automatically with Windows.  

---

## 3. Workflow usage

Outevia runs in the background and can be called instantly while you are reading documents or email messages containing hard‑to‑read images.

- When Outevia is running, it waits for the default or custom hotkey, so you can keep reading and maintain focus on the text and your current position in the document.  
- When you find an image with hard‑to‑read details, click the image to select it and press the shortcut. Outevia immediately opens the image in its viewer with dedicated tools and advanced zoom.  
- After starting Outevia in the background, press **Ctrl+Shift+0** or the key combination you configured in **Settings** to trigger immediate capture of the selected image. The shortcut can be customized from the Settings panel.  

### Reopen from the system tray

- After using Outevia, if you click the **X**, the application does not fully close: it stays active for future reuse and its icon remains in the system tray.  
- You can open Outevia at any time through **System Tray → Open** to view the latest capture, or use **Ctrl+Alt+0** after selecting the image.  
- Clicking the **bin** icon lets you delete the latest capture.  
- If you want to clear the full Windows Clipboard history, use the **Win+V** command.  

---

## 4. Image viewing

Operationally, Outevia is very simple to use.

1. Open the document or email message.  
2. Use the mouse pointer to click the image you want to view in Outevia. The image must show clear selection markers.  
3. Press the default **Ctrl+Alt+0** shortcut or the custom one you configured in Outevia settings.  
4. The image will be shown in Outevia and you will be able to use zoom, text, drawing and OCR tools.  
5. If the image cannot be selected, screen snipping starts automatically, captures the area and sends it into Outevia while keeping the same workflow.  

---

## 5. Work tools

Outevia includes tools to annotate, read and analyse captured content quickly.

### Text

The **Text** tool lets you add notes, references or comments directly onto the image opened in Outevia.

### Drawing

The **Drawing** tool is useful for circling areas, drawing arrows or underlining important details while analysing PDFs, documents or email messages with selectable images.

### OCR

The **OCR** tool recognises text inside the captured image so you can extract and reuse it more quickly. After using OCR, the recognised text is copied to the clipboard and can be pasted elsewhere.

### Tool list

- Restore original size  
- Rotate the image to the right  
- Rotate the image to the left  
- Enable OCR tool  
- Enable Text tool  
- Enable Drawing tool  
- Copy the image including any text and drawings applied with Outevia tools  
- Save the image to disk including any text and drawings applied with Outevia tools  
- Keep Outevia always on top  
- Clear the current Outevia view  
- Open Outevia settings  

---

## 6. Zoom and navigation

Outevia is designed to inspect image details in its external viewer without zooming the whole document and losing focus on the paragraph you are reading.

- Use Outevia arrows for progressive zoom or **Ctrl + mouse wheel**.  
- Click with the mouse pointer to move around the enlarged image.  
- Use the restore command to return to the original view.  

---

## 7. Clipboard and OLE

- Outevia stores captured images in the temporary Windows clipboard.  
- Clipboard history appears in the right‑hand side panel and supports text, images and OLE objects from compatible applications.  
- The Windows clipboard can be cleared by opening clipboard history with **Win+V** or simply by restarting the system.  

---

## 8. Screen snipping

When the image cannot be selected, Outevia switches to screen snipping to manually capture the desired area.

### Alternative capture

- If Outevia cannot directly detect the selected image inside the document or email, it enables screen snipping mode.  
- Select the area of interest with the mouse: the captured image opens in Outevia and can be zoomed, annotated or analysed like any other capture.  

### After snipping

After manual capture you can use the same tools available for automatically detected images, including zoom, text, drawing and OCR.

---

## 9. Settings and tray icon

Application preferences let you choose the shortcut combination and other useful Outevia settings.

### Preferences

From the **Settings** panel you can configure:

- **Translation:** choose language (Italian or English)  
- **Behaviour:** enable OCR and screen snipping  
- **Theme:** enable dark, light or system mode  
- **Tools:** enable the text or drawing tool  
- **Global shortcut:** choose the key combination that activates Outevia  
- **Logs:** record all events in a defined path  
- **Start with Windows:** launch Outevia automatically with Windows  

### Tray icon

From the tray icon you can quickly recall Outevia, access essential commands and verify that the application is running in the background.

---

## 10. Updates

Keeping Outevia up to date helps you receive fixes, improvements and new features.  
Updates are published on the updates page.

---

## Links

- Website: <https://outevia.com/>  
- Download: <https://outevia.com/download.php>  
- Guide: <https://outevia.com/guide.php>  
- .NET runtime: <https://dotnet.microsoft.com/en-us/download>  
