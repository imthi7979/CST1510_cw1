"""
RECORD CHECK  -  my version
===========================

Name  : mohammed imthiyas
Lane  : Cyber
Date  : 22/10/2026

Run it:   python template.py

.
"""


class Record:
    def __init__(self, label, value, limit):
        self.label = label
        self.value = value
        self.limit = limit

    def status(self):
        percentage = (self.value / self.limit) * 100

        if percentage >= 100:
            return "OVER LIMIT"
        elif percentage >= 90:
            return "WARNING"
        else:
            return "OK"


# Create records
records = [Record("R-001", 87.0, 100.0),
    Record("R-002", 120.0, 100.0),
    Record("R-003", 95.0, 100.0)]

# Print 
for record in records:
    print()
    print("=" * 34)
    print(f" RECORD CHECK - {record.label}")
    print("Label:", record.label)
    print("Value:", record.value)
    print("Limit:", record.limit)
    print("Status:", record.status())
    print("=" * 34)
    
   



