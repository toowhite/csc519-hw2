# HW2-Template

### Screencast
Link: https://youtu.be/quOVqF0bW6w

### Enable --ask-vault-pass

You need to modify `run-ansible.sh` code to enable ask-vault-pass. 

Modify Line 21 to `ansible-playbook $PLAYBOOK -i $INVENTORY --ask-vault-pass`

The password is the one TA requires.

### Implementation
- Extra requiremnts implemented are 
 1) add team automatically using mattermost cli 
 2) setting up email notification


