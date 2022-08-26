# setup_file

1. Download the file & upload the right path
  - Download the file and move the file to the location where pip.exe is located
2. Path Settings
  - Check the "pip list" is working in cmd
3. SSL Settings
  - If you do not want to verify SSL certificates, change the code in the sessions.py file
  - self.verify=True-> self.verify=False (line : #: SSL Verification default.)
  - Location : C:\Users\{user_name}\AppData\Local\Programs\Python\Python36-32\Lib\site-packages\pip\_vendor\requests\sessions.py
5. pip upgrade
  - python -m pip install --no-index --find-links="./" pip-22.2.2-py3-none-any.whl
6. download all library
python -m pip install --no-index --find-links="./" -r final_list.txt
7. Download the 'VC_redist.x64'
  - Install the 'VC_redist.x64' file to use TensorFlow 
