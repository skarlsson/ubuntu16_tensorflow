# README #

```
sudo apt -y update
sudo apt-get install ssh ansible git aptitude

git config --global user.email "your@email"
git config --global user.name "your name"

git clone https://github.com/skarlsson/ubuntu16_tensorflow.git
cd ubuntu16_tensorflow
```

```
ansible-playbook -i "localhost," -c local initial-tensorflow-ubuntu.yml --ask-sudo-pass 
```

#### tensorflow (with GPU)
```
ansible-playbook -i "localhost," -c local tensorflow.yml
```


