## Smart Building Access Control Dataset Descriptions 
The access control dataset consists of 10,000 rows and 11 columns that are useful for access control. The longitude and latitude columns provide information on the location of the access attempt, which can help detect unauthorized access attempts from outside the authorized area. The country column can also provide information on the location, which is useful in the access decision. The day of access and time of access columns provide information on when the access attempt was made, which can be used to detect unusual activity outside of normal business hours. The time taken column provides information on the time it takes to enter a password, which can be used to detect suspicious activity or possible password guessing attacks. The browser language and user agent columns provide information on the type of device and browser used, which can be used to detect unusual access attempts from unknown or unauthorized devices. Finally, the screen width and screen height columns provide information on the screen dimensions, which can be used to detect unusual access attempts from devices with unusual screen sizes or aspect ratios. The final column contains the decision on whether the access is granted or denied.

### Considered Features for the Dataset:

#### Longitude and Latitude: 
These two columns are numerical and represent the geographic location of the access attempt. This information can be used to determine whether the access is coming from a known or suspicious location. These columns are of type float.

#### Country:
This categorical column represents the country from where the access attempt is being made. The entrees of this column are strings.

#### Day of Access:
This categorical column represents the day of the week when the access attempt was made. It is of type string.

#### Time of Access:
This numerical column represents the time of day when the access attempt was made.

#### Time Taken (ms):
This numerical column represents the time it took for the user to enter the password in milliseconds. It can be used to detect automated attempts to guess passwords or brute force attacks. It is of type integer.

#### Browser Language:
This categorical column contains a string that represents the language of the user's web browser.

#### User Agent:
This categorical column represents the user agent string of the user's web browser. It can be used to identify suspicious or malicious web browser behavior.

#### Screen Width and Screen Height:
These two numerical columns represent the dimensions of the user's screen.

#### Decision (Access Control):
This column represents whether the access attempt was granted or denied (binary) based on the access control policy.
