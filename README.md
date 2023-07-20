# Data Pipeline (CI/CD)



# Step 1.  Jenkins installation commands

1. sudo apt update

2. sudo apt install openjdk-11-jre

3. java -version

4. curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \ /usr/share/keyrings/jenkins-keyring.asc > /dev/null

5. echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \ https://pkg.jenkins.io/debian-stable binary/ | sudo tee \ /etc/apt/sources.list.d/jenkins.list > /dev/null

6. sudo apt-get update

7. sudo apt-get install jenkins

8. sudo systemctl enable jenkins

9. sudo systemctl start jenkins

10. sudo systemctl status jenkins

# End Step 1


# Step 2. 

1. sudo cat /var/lib/jenkins/secrets/initialAdminPassword

2. 
