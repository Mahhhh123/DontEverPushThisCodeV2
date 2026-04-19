# Don't ever push this code to the production
---
This is a highly vulnerable website designed to be serve as a workshop
assets on the security topic of Software Engineering Course (2110423) (2025/2)

## How to run
1. Clone this repository
2. Run `docker build -t highly-exploitable-site .`
3. Run `docker run --rm -p 3000:8080 highly-exploitable-site`
4. Visit `http://localhost:8080`
5. Run SAST , and DAST tools to verify the vulnerability of the site
6. Press Ctrl + C or CMD + c to kill the process once done

## Security Notice
This is not a real website. One must not (ever) deploy this in the production server 