# investigate-a-dataset
An exploration why people missed their appointments. NO SHOW.
We investigated the correlation between some of the characteristics of the patients and whether they missed or showed to their appointment. And these are the results of these analyses:

patients from 12 to mid-30s are more likely to miss their appointments

kids and patients in their 60s, 70s, and 80s are more likely to show to their appointments

There is no correlation between gender alone and missing the appointment.

The neighborhoods with most patients showing to their appointments have low patients numbers. So, we couldn't conclude that these neighborhoods have a higher chance that patients won't miss their appointments.

Receiving an SMS did not increase the chance that the patient would show to their appointment.

limitations
The period when the data collected was just nearly two months, and this short period doesn't make the data reliable to make a strong correlation

There was no explanation of how the data was collected, and if it was collected in a way that makes these analyses more reliable.

The Handcap and SMS_received columns weren't explained clearly on the dataset page.

The dataset didn't explain why the patient come to the doctor, which may give an additional explanation about why they miss their appointments.

from subprocess import call
call(['python', '-m', 'nbconvert', 'Investigate_a_Dataset.ipynb'])
0
