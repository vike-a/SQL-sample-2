# UPDATE books_in_use
# SET fine_amount = (DATEDIFF(return_date, issue_date) - return_period) * 8.45
# WHERE return_date IS NOT NULL and DATEDIFF(return_date, issue_date) > return_period;
