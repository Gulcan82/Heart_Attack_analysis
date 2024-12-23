# Kaggle Heart Attack Analysis: Step-by-Step Guide

## Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and log in.
2. Click on the `+` icon in the top right corner and select `New repository`.
3. Name your repository `Heart_Attack_analysis`.
4. Add a description (optional).
5. Choose `Public` or `Private`.
6. Click `Create repository`.

## Step 2: Clone the Repository Using PowerShell
1. Open PowerShell.
2. Navigate to the directory where you want to clone the repository:
    ```powershell
    cd C:/Users/gulca/Documents/
    ```
3. Clone the repository:
    ```powershell
    git clone https://github.com/your-username/Heart_Attack_analysis.git
    ```
4. Navigate into the cloned repository:
    ```powershell
    cd Heart_Attack_analysis
    ```

## Step 3: Create a Virtual Environment

1. Create a virtual environment:
    ```powershell
    python -m venv .venv
    ```
2. Activate the virtual environment:
    ```powershell
    .\.venv\Scripts\Activate
    ```

3. In PowerShell, create a new branch:
    ```powershell
    git checkout -b analysis-branch
    ```
4. Open Visual Studio Code (VSCode).
    ```powershell
    code .
    ```

## Step 4: Download the Dataset from Kaggle
1. Go to the Kaggle dataset page and download the dataset.
2. Extract the dataset files if necessary.

## Step 5: Paste the Dataset into VSCode
1. Open Visual Studio Code (VSCode).
2. Open the cloned repository folder in VSCode.
3. Copy the downloaded dataset files into the repository folder.


## Step 6: Create folder name data and inside the folder create a Jupyter Notebook File with the ending .ipynb

1. Create folder with the name `data`, in this folder
create a new file and save it as `analysis.ipynb`.



## Step 8: Stage, Commit, and Push the New Branch
1. Stage the changes:
    ```powershell
    git add .
    ```
2. Commit the changes:
    ```powershell
    git commit -m "Initial analysis setup with dataset and virtual environment"
    ```
3. Push the new branch to GitHub:
    ```powershell
    git push origin analysis-branch
    ```

## Step 9: Merge the New Branch into the Main Branch
1. Open your terminal.
2. Navigate to your repository directory.
    ```sh
    cd /path/to/your/repository
    ```
3. Ensure you are on the `main` branch.
    ```sh
    git checkout main
    ```
4. Merge the `gulcan` branch into the `main` branch.
    ```sh
    git merge gulcan
    ```
5. Push the changes to GitHub.
    ```sh
    git push origin main
    ```
6. Delete the `gulcan` branch if desired.
    ```sh
    git branch -d gulcan
    git push origin --delete gulcan
    ```

Congratulations! You have successfully set up your Kaggle Heart Attack Analysis project.

## Support

If you found this guide helpful and would like to support my work, consider buying me a coffee:

[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/gulcan)