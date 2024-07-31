# Build a Chatbot with Custom Slots


# Project Overview: 


✅ A new Lex chatbot called BankerBot.
✅ WelcomeIntent set up.
✅ FallbackIntent customised, i.e. your BankerBot says a customised error message if it doesn't understand the user's input.

![image](https://github.com/user-attachments/assets/fd88c4c8-71dc-4c58-8f25-699f0179c1c3)

# Step 1: Select Create bot.

2. Select Create a blank bot.

3. For Bot name, enter 

4. For Description, enter 

5. Under IAM permissions, select Create a role with basic Amazon Lex permissions. We'll be using it to call another service called Lambda in a future project!

6. Under Children’s Online Privacy Protection Act (COPPA), select No.

7. Under Idle session timeout, keep the default of 5 minutes.


![2024-07-31_15h13_40](https://github.com/user-attachments/assets/d2f3b201-63c0-464e-b42e-c3a24d406def)

![2024-07-31_15h13_56](https://github.com/user-attachments/assets/622d3262-b9a1-4d2e-b167-d6408125c8dc)


# Step 2: Set Up WelcomeIntent


1. Under Intent details, enter 
2. for the Intent name.
3. Add the description 
4. Scroll down to the Sample utterances panel.
5. Click the Plain Text button.


![2024-07-31_15h16_08](https://github.com/user-attachments/assets/1ecea391-1339-420f-8c51-9a59ae392615)


![2024-07-31_15h18_25](https://github.com/user-attachments/assets/2b917d6d-4bb9-462e-aacb-83510f6ad5e9)


1. Scroll down to Closing response, and expand the speech bubble for Response sent to the user after the 2. intent is fulfilled.
3. In the Message field, enter the following message:

![2024-07-31_15h19_28](https://github.com/user-attachments/assets/0828a27a-a975-4edc-bc1e-a9a836491aac)


# Step 3: Manage FallbackIntent


![2024-07-31_15h25_40](https://github.com/user-attachments/assets/12d9499b-e270-4d6e-bb3d-9fe96949f6c8)




# Build and Test

![2024-07-31_15h26_57](https://github.com/user-attachments/assets/3a6a1eeb-fb67-44c2-a1c2-f55490f4770c)


# Step 4: Create a Custom Slot for Account types

1. Choose Add slot type.
2. From the dropdown, choose Add blank slot type.
3. Enter for the Slot type name.
4. Choose Add.


![2024-07-31_16h37_24](https://github.com/user-attachments/assets/4ba70134-51a3-477e-bfe6-4f45b7327b0a)


![2024-07-31_16h37_42](https://github.com/user-attachments/assets/ce77eef5-11b1-41f0-9087-25fceb3dd056)

![2024-07-31_16h40_53](https://github.com/user-attachments/assets/b887c246-cd50-4af1-9e18-82b42f338d24)





1. In the Values field, enter 

2. Select Add value, or just press Enter on your keyboard.

3. Do the same for 
Enter , and add a few synonyms in the second field.
4. Press on your keyboard after every time you add in a new one:

5. Choose Add value to finish up your work for Credit.


![image](https://github.com/user-attachments/assets/d782a5a2-62bd-4f1a-8a95-876615f4f7e9)


![2024-07-31_16h40_53](https://github.com/user-attachments/assets/9607e482-22ef-42d8-aa17-aef7887720b7)


# Step 5 : Create the CheckBalance intent

1. In your left hand navigation panel, head back to Intents.
2. Choose Add intent, then Add empty intent.


![2024-07-31_16h44_20](https://github.com/user-attachments/assets/b5855128-b79c-4f18-bad3-fd6012c14617)


![2024-07-31_16h56_58](https://github.com/user-attachments/assets/d75510ff-6600-4395-a7e1-5b296f2ca7f2)


![image](https://github.com/user-attachments/assets/d6d5e39e-a6a6-4dd6-a811-b25a7fbe5ec0)
