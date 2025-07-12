# o11-v3

## Installation

1. **Install ffmpeg**  
   Make sure `ffmpeg` is installed on your system. For Debian/Ubuntu, run:
   ```
   sudo apt-get install ffmpeg
   ```

2. **Upload Files**  
   Upload all the provided files to a directory on your server, for example:
   ```
   /home/o11-v3
   ```
   _Keep all files inside this folder._

3. **Set Permissions**  
   Make the launcher executable:
   ```
   chmod +x v3p_launcher
   ```

4. **Run the Launcher**  
   Start the application with:
   ```
   ./v3p_launcher -p 1234
   ```

   To see all available options, run:
   ```
   ./v3p_launcher -h
   ```

   To run in the background, use:
   ```
   ./v3p_launcher -p 1234 &
   ```

5. **Access the Web Interface**  
   Open your browser and visit:
   ```
   http://yourserverip:1234
   ```

   Default login credentials:
   ```
   Username: admin
   Password: admin
   ```

   _You can change the username and password in the users section of the web interface._

6. **Adding Providers and Streams**  
   - You can add a provider using the header dropdown menu.
   - After adding a provider, configure streams in the "Provider Config" section.

---

**Special thanks to ## DRMLab.io**
