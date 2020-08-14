# ansible_tag_inheritance
A quick exploration of where tags must be used when importing and including tasks from a playbook.

# Usage:
##  Baseline without tags:
 $ ansible-playbook test_tags.yaml
##   Running with tags:
 $ ansible-playbook test_tags.yaml --tags bar
