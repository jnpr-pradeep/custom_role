# custom_role
tar -xvzf custom_role.tgz
cd custom_role

Step1:
  a) For python2
    pip install virtualenv
    virtualenv .venv

  b) For python3
    pip3 -m venv .venv

Step2:
  source .venv/bin/activate

Setp3:
  pip install -r requirements.txt

Step4:

  For help
    python custom_role.py -h

  Acutal command:
    python custom_role.py -pr leaf,spine -j2 /tmp/test.txt -pwd c0ntrail123 -np juniper-mx
