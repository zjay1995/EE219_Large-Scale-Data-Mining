figures
set dpi=300  # If working loacally, upload figures to the shared folder under '/report/figures'

naming, say for question 5: "q5-****.png"
# -----------------------------------------------------------
results

suggested:
pickle.dump(variable_name, open('results/' + filename, 'wb'))
variable_name = pickle.load(open('results/' + filename, 'rb'))

naming： Also put a question index at the front

upload results to the shared folder under '/results'
# -----------------------------------------------------------
ipynb

Up to you.
Either work on the starter file, RENAME and upload or whatever that is convenient to you.

# -----------------------------------------------------------
report

For this part, you CAN overwrite when uploading your own part.

# -----------------------------------------------------------
utilities.py

for holding udf to keep the notebook clean.
Either work on the file, RENAME and upload, or whatever.

