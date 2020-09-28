# Python-Compound-Mortgage
'''
Python - Calculate your mortgage over a designated period of time
'''

principal = #initial investment
interestRate = #interestrate
years = #years
print(f'Value of Principal of ${principal}\
      at {(interestRate*100):.2f}% interest rate')
for i in range(years + 1):
    print(f'... after {i} years: ${principal:.2f}')
    principal += principal*interestRate
