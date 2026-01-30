# Task 1: Run Ubuntu Container with Environment Variable

## Objective
Run an Ubuntu container, pass an environment variable using `-e`, verify it inside the container, then stop the container and observe the behavior.

---

## Steps

### Step 1: Run Ubuntu Container
Run the following command to start an Ubuntu container and pass the environment variable:

```bash
docker run -it -e COLLEGE=CSE ubuntu bash

docker run -it -e COLLEGE=CSE ubuntu bash
echo $COLLEGE
```
<img width="1105" height="179" alt="image" src="https://github.com/user-attachments/assets/ae6e9d2f-9843-4525-a1da-b30c0178c0fb" />
