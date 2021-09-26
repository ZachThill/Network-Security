# Configuring a Strong Password Policy
- Source:
Narayana, Allen, R., Osee, Tinker, Ben, Don, Aqel, A., George, Mahroof, A., Orazio, Andreplusplus, Victor, Starland, M., Azz, Bettermann, V., Rahul, M., &amp; Hwang, K. (2021, August 23). How to configure a domain password policy. Active Directory Pro. Retrieved September 26, 2021, from https://activedirectorypro.com/how-to-configure-a-domain-password-policy/. 


**Step 1 - Go to Local Group Policy in Active Directory** 

 - Open Active Directory
 - 1. Open the group policy management console 
 - 2.  Expand Domains, your domain, then group policy objects
 - 3. Right click the default domain policy and click edit
 - 4. Now navigate to Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Password Policy
 - 5. Minimum password length: The default is 7. CIS Benchmark recommendation: Minimum password length is set to 14 characters
 - 6. Password must meet complexity requirements: Enabled
 - - Contain characters from three of the following four categories:
 - - English uppercase characters (A through Z)
 - - English lowercase characters (a through z)
 - - Base 10 digits (0 through 9)
 - - Non-alphabetic characters (for example, !, $, #, %)
 - 7. Store passwords using reversible encryption: ALWAYS DISABLE
 - - NOTE: CIS Benchmark password setting:
 - - - Enforce Password History: 24
 - - - Maximum password age: 60 or fewer days
 - - - Minimum password age: 1 or more
 - - - Minimum password length: 14
 - - - Password must meet complexity: Enabled
 - - - Store passwords using reversible encryption: Disabled



