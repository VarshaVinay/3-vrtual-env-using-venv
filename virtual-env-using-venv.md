### Link: https://youtu.be/Kg1Yvry_Ydk


### Walk through
    1. pwd

    2. cd sample-project

    3. pip3 list

    4. python3 -m venv my-proj-env

    5. activation: 
            source my-proj-env/bin/activate

    6. which python
       output: /home/welcome/Desktop/sample-project/my-proj-env/bin/python

    7. pip3 list
    output: 
            pip (9.0.1)
            pkg-resources (0.0.0)
            setuptools (39.0.1)

    8. pip3 install requests
    
    output: 
        certifi (2022.6.15)
        charset-normalizer (2.0.12)
        idna (3.3)
        pip (9.0.1)
        pkg-resources (0.0.0)
        requests (2.27.1)
        setuptools (39.0.1)
        urllib3 (1.26.11)

    9. pip freeze  
        this will give the order/sequence of packages to be written in requirement.txt file

        certifi==2022.6.15
        charset-normalizer==2.0.12
        idna==3.3
        pkg-resources==0.0.0
        requests==2.27.1
        urllib3==1.26.11

    10. type pip
        output - pip is aliased to `pip3'

    11. pip freeze > requirements.txt
        One command to get the order of the packages and redirect the output to requirements.txt file

        cat requirements.txt 
        to see the contents of the file

    12.deactivation: 
        deactivate 
        rm -rf my-proj-env

### 13. General flow of virtual env activation and install pcks and deactivation
    mkdir <prj-name>

    cd <prj-name>

    python3 -m venv <prj-name>/venv

    source <prj-name>/venv/bin/activate

    pip install -r requirements.txt

### 14. Important For git

Let us add the venv folder in .gitignore 


