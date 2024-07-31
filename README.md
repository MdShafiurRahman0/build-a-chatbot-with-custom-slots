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

## Build and Test








