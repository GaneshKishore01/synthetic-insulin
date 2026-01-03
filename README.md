<img width="1920" height="1080" alt="image" src="https://github.com/GaneshKishore01/synthetic-insulin/blob/main/src/GK_ProductionsLogo.png" /># Paper on 
A Software designed for tracking torrents and monitoring peers conneted to it.
# **Description**

## **What it is**
Tradinitonal biochemical productions rely on Saccharomyces cerevisiae (baker's yeast), in which one of the steps is to break open the yeast cells to take seperate the biochemical product from the yeast. This step however is monetarily and financialy costly since the yeast cells have to be replenished.

In the proposed methord, we plan to use 
- Searching for magnets across multiple sites at once  
- Tracking peers by hosting your own file  
- Viewing IP/location info of connected peers  

---

## **How it works**
- **Peer detection & hosting/tracking:**  
  Uses **qBittorrent** and **ipwhois** to detect peers and fetch geo-location/info.

- **Magnet search:**  
  Uses **Jackett** to aggregate torrent search results from multiple indexers.
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/GaneshKishore01/synthetic-insulin/blob/main/src/F-insulin%20A1.png" width="400"/>
    </td>
    <td align="center">
      <img src="https://github.com/GaneshKishore01/synthetic-insulin/blob/main/src/F-insulin%20A2.png" width="400"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/GaneshKishore01/synthetic-insulin/blob/main/src/F-insulin%20docked.png" width="400"/>
    </td>
    <td align="center">
      <img src="https://github.com/GaneshKishore01/synthetic-insulin/blob/main/src/GK_ProductionsLogo.png" width="400"/>
    </td>
  </tr>
</table>

---

## **Instructions**
1. Download `MSMT.zip` from releases.
2. **Extract** the contents of `MSMT.zip`
3. **Copy** the `MTSM` folder from `/assets` into:  
   `C:\Users\GANESH\AppData\Roaming\`
4. **Configure** the Jackett and qBittorrent ports in the **Settings** tab
5. Enjoy!

---
