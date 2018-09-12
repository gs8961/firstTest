# firstTest
{
"projectId": "kx4fif"
}

cypress run --record --key 6708aeed-604c-4749-9795-6a1c1893c65a

VISIT https://www.americantitleinc.com/ati/

GET .navbar-nav
 -CONTAINS About Us
 -CLICK
 
GET .dropdown-menu
 -CONTAINS Core Values
 -CLICK
 
-ASSERT expected /About-Us/Core-Values to include Core-Values
