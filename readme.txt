sudo apt-get install wget apt-transport-https gnupg lsb-release

wget -qO - https://aquasecurity.github.io/trivy-repo/deb/public.key | gpg --dearmor | sudo tee /usr/share/keyrings/trivy.gpg > /dev/null

echo "deb [signed-by=/usr/share/keyrings/trivy.gpg] https://aquasecurity.github.io/trivy-repo/deb $(lsb_release -sc) main" | sudo tee -a /etc/apt/sources.list.d/trivy.list

sudo apt-get update

sudo apt-get install trivy -y











http://ae1c29b500b804026b340623844c0642-344190043.ap-south-1.elb.amazonaws.com/

git token :  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

l1,2
GuruSchools Training is inviting you to a scheduled Zoom meeting.

Topic: Aws DevOps
Time: Apr 16, 2024 07:00 AM India

Join Zoom Meeting
https://us02web.zoom.us/j/87137372096?pwd=bW5aNEZNNnEwZHdzdnlLZHJhUk1aUT09

Meeting ID: 871 3737 2096
Passcode: 385360
apiVersion: networking.k8s.io/v1
kind: NetworkPolicy
metadata:
  name: allow-specific-pod
  namespace: your-namespace
spec:
  podSelector:
    matchLabels:
      app: your-app
  policyTypes:
  - Ingress
  - Egress
  ingress:
  - from:
    - podSelector:
        matchLabels:
          app: allowed-app
    ports:
    - protocol: TCP
      port: 80
  egress:
  - to:
    - podSelector:
        matchLabels:
          app: allowed-app
    ports:
    - protocol: TCP
      port: 80

---

One tap mobile
+16465588656,,87137372096#,,,,*385360# US (New York)
+16469313860,,87137372096#,,,,*385360# US

---

Dial by your location
• +1 646 558 8656 US (New York)
• +1 646 931 3860 US
• +1 669 444 9171 US
• +1 669 900 9128 US (San Jose)
• +1 689 278 1000 US
• +1 719 359 4580 US
• +1 253 205 0468 US
• +1 253 215 8782 US (Tacoma)
• +1 301 715 8592 US (Washington DC)
• +1 305 224 1968 US
• +1 309 205 3325 US
• +1 312 626 6799 US (Chicago)
• +1 346 248 7799 US (Houston)
• +1 360 209 5623 US
• +1 386 347 5053 US
• +1 507 473 4847 US
• +1 564 217 2000 US

Meeting ID: 871 3737 2096
Passcode: 385360

Find your local number: https://us02web.zoom.us/u/keCnlMW5l8

