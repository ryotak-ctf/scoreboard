# How to Submit
**Important:** Please debug your answer before submitting it. GitHub has a strict rate limit for creating the draft security advisory, and you may be rate limited if you submit answers too frequently.  

In this CTF, you need to submit answers via [Privately reporting a security vulnerability](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) feature of GitHub.  
To submit an answer, please follow the steps below:  

1. Go to [Open a draft security advisory](https://github.com/ryotak-ctf/scoreboard/security/advisories/new) page of the `ryotak-ctf/scoreboard` repository.  
2. Enter the ID of the problem you want to submit an answer for in the `Title` field. (You can check the `Challenge ID` in the description page of each challenges.)  

![292617072-895bbe17-26db-4ae5-9616-cf500fa57a89](https://github.com/ryotak-ctf/challenges/assets/49341894/670e2ced-98f6-4a19-9660-99cf9076d02a)

3. Enter the answer in the `Description` field. (e.g. `sanity check` for this problem). You need to clear the pre-filled contents before writing the answer.  

![292617268-75bb1949-a4b0-4c5c-9dde-8ad4358d728a](https://github.com/ryotak-ctf/challenges/assets/49341894/fcebe7ad-80b6-499f-bbe1-6d69c7f90105)

4. Click `Create draft security advisory` button.

![292617305-cfc25fa8-47dc-4991-ad6a-6dead50ad96c](https://github.com/ryotak-ctf/challenges/assets/49341894/fb9c53ff-ca74-4d2b-acac-f8fa43581a5d)

5. The bot will automatically close the draft security advisory, and will start validating your answer in GitHub Actions.
6. Once your answer is validated, you will be notified via the issue.  

![292617207-7631c792-34f0-4866-9b00-b21a3a1d54d8](https://github.com/ryotak-ctf/challenges/assets/49341894/71939a70-9838-4967-9ca4-0c1ca49bde8c)

7. If your answer is correct, the bot will automatically adds you to the scoreboard.  

# If you found an actual vulnerability
If you found an actual vulnerability (for example, a vulnerability that allows you to tamper with the repository contents), please report it to the [vulnerability submission form](https://hackerone.com/93202d34-3ae1-407c-9673-46cc33febc1e/embedded_submissions/new).  
Please note that all challenges are intentionally vulnerable, and you should not report vulnerabilities in the challenges to this form.    
