# Dev-repo
1st Command : leo run mint <type_aleo_address> <type_amount>u64


2nd command: leo run transfer "<Token_Record>" <to_address> <amount>u64
We were  able to use the generated record from 1st command to input into the second command's first input (remember) and then our to address and amount 
leo run combine_hash_owner_receiver <type_your_address> <type_friend_address>
This has only 2 inputs where first input is owner address (self.caller) and second input is the  receiver address

third command:generated private key in your .env needs to be change to that of your Leo wallet private key
run program,copy code from built/aleo.main then deploy with fee when complete get signature with wallet address

Records are used to store user/data components. To view a record, you need a view key which you need to share only to  trusted parties, View key doesn't compromised Leo wallet but can lead to someone monitoring your data/asset
