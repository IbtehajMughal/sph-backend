# Smart Product Hunting

## How to run node js server

create a new .env file and copy the content from env.example or just rename the .env.example file to .env

```bash
  yarn install
  yarn run dev
```

## Instructions for dataset to train AI model

Download the dataset files from given google drive link and place them one by one in ai folder

```bash
  https://drive.google.com/drive/folders/1ArF5PU6p9Lz8FzOUgy3xX7As87ZXOfVM?usp=sharing
```

## How to run python server

assuming you already have python installed
First open terminal from project directory and go to ai folder

```bash
  cd ai
```

Create and activate a virtual envirnoment

```bash
  python3 -m venv venv
  cd venv\Scripts
  activate
  cd ../../
```

or

```bash
  python3 -m venv venv
  path\to\venv\Scripts\activate.bat
```

After creating and activating virtual envirnoment
We ll install required libraries/packages from requirment.txt file

```bash
pip3 install -r requirements.txt
```

Once all packages/libraries are installed
run the server using the command below

```bash
python3 pyserver.py
```
