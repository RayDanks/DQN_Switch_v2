# DQN_Switch_v2
This is a Multi Agent Reinforcement Learning system which I have implemented.
Analysis of the system is seen in the last cell of the notebook.

IMPORTANT: Currently, there seems to be an error with the Gym Import. Pillow updated on April 1, 2020 and thus the import of the Switch-v2 Gym has been causing errors while importing. This means that some tweaks made to the system class have not been tested, although the logic of the code is still the same and has been tested adequately and analysed.

Moreover, once this issue is fixed, it is my intent that the replay memories/buffers will be replaced by deques and random sampling will be used, in order to dramaticallty reduce the complexity of the system and raise efficiency. This cannot be added until these issues have been fixed and the system can be properly tested again.

To Fix: Note that the code is wrapping quite extremely on the GitHub viewer, which is undesirable and looks messy. I intend to change this in order to make the code more readable, although in Google Collab (where the code was written), the lines are not wrapped in such a way, hence it has not hindered operational development.
