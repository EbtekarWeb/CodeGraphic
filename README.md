# CodeGraphic
Test Wordpress space for CodeGraphic website

# Prerequisites
### XAMPP 8.2.12 x64 (Need installing for all PC) <sup>[↗️From Assets Library](https://github.com/EbtekarWeb/Assets_Library/blob/main/README.md#xampp)</sup>

# Initializing - in 3 steps
### Step 1: Start Apache and MySQL in XAMPP

1. **Open XAMPP Control Panel:**
   - Locate the XAMPP Control Panel application and open it.

2. **Start Apache:**
   - In the control panel, find the **Apache** module.
   - Click the **Start** button next to Apache. The status should change to "Running."

3. **Start MySQL:**
   - Similarly, find the **MySQL** module in the control panel.
   - Click the **Start** button next to MySQL. The status should also change to "Running."

4. **Verify Services:**
   - Open your web browser and go to `http://localhost`. You should see the XAMPP dashboard, indicating that Apache is running.
   - For MySQL, you can go to `http://localhost/phpmyadmin` to access the phpMyAdmin interface, indicating MySQL is running.

### Step 2: Create Database in phpMyAdmin & Import Database

1. **Access phpMyAdmin:**
   - Open your web browser and go to `http://localhost/phpmyadmin`.

2. **Log In:**
   - If prompted, log in with your MySQL username and password. The default username is `root` and there is no default password.

3. **Create a New Database:**
   - In the phpMyAdmin dashboard, click on the **Databases** tab at the top.
   - In the `Create database` field, enter `wp_codegraphic_db` for new database.

4. **Click Create:**
   - Click the **Create** button to create your new database.

5. **Database Created:**
   - You should see a message confirming that the database has been created successfully.

6. **Verify the Database:**
   - Your new database should now appear in the list on the left sidebar under the **Databases** tab.

7. **Go to the Import Tab:**
   - Click on the **Import** tab at the top of the page.

8. **Choose the SQL File:**
   - Under the `File to import` section, click on the **Choose File** button.
   - Download [wp_codegraphic_db.sql](https://github.com/EbtekarWeb/Assets_Library/releases/download/wp_codegraphic_db/wp_codegraphic_db.sql).
   - Navigate to the location of the `wp_codegraphic_db.sql` file on your computer and select it.

9. **Start the Import:**
   - Ensure that the format is set to `SQL`.
   - Click on the **Go** button at the bottom of the page to start the import process.

10. **Verify the Import:**
    - Once the import is complete, you should see a success message.
    - Check the database tables to ensure that the content has been imported correctly.
### Step 3: Clone GitHub Repository to `C:\xampp\htdocs\codegraphic` Using GitHub Desktop

1. **Install GitHub Desktop:**
   - If you don't already have GitHub Desktop installed, download and install it from [GitHub Desktop](https://desktop.github.com/).

2. **Open GitHub Desktop:**
   - Launch the GitHub Desktop application.

3. **Sign In to GitHub:**
   - If prompted, sign in to your GitHub account.

4. **Clone Repository:**
   - Click on the **File** menu, then select **Clone repository**.
   - In the `Repository` tab, click on the **URL** option.
   - Enter the URL of the repository to clone. URL: `https://github.com/EbtekarWeb/CodeGraphic`.

5. **Choose Local Path:**
   - Click on the **Choose...** button to select the location where you want to clone the repository.
   - Navigate to `C:\xampp\htdocs` and create a new folder named `codegraphic` (if it doesn't already exist).
   - Select the `codegraphic` folder and click on **Select Folder**.

6. **Clone the Repository:**
   - Click on the **Clone** button to start the cloning process.
   - GitHub Desktop will clone the repository to `C:\xampp\htdocs\codegraphic`.

7. **Verify the Clone:**
   - Once the cloning process is complete, navigate to `C:\xampp\htdocs\codegraphic` in File Explorer to ensure that the project files have been successfully cloned.

8. **Access to Local WordPress Site:**
    - Open your web browser and navigate to `http://localhost/codegraphic` to access your local WordPress site.

### Finish Up!
Everything is set up and ready to go!
