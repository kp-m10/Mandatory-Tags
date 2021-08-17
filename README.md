# Mandatory-Tags

1) terraform init

2) terraform -var 'subscription=your_subscription_id' -var 'tag_list=["Environment","Application","Owner","Business Unit","Criticality","Data Classification","Billing Identifier"]'

3) terraform apply -auto-approve -var 'subscription=your_subscription_id' -var 'tag_list=["Environment","Application","Owner","Business Unit","Criticality","Data Classification","Billing Identifier"]'
