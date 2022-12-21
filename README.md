# ubuntu-issue


# Troubleshooting

## ERROR
![image](https://user-images.githubusercontent.com/69744247/208802025-8adf3f34-79f6-4410-b514-99cab13fd633.png)

Solution 1:
Could be caused by incorrect proxy settings.

Run the following commands then try to git clone again
```
git config --global --unset http.proxy
git config --global --unset https.proxy
```

Solution 2:
Could be caused by incorrect nameservers.

Run the command shown below 
```
sudo nano /etc/resolv.conf
```
Change nameserver to 8.8.8.8, save the file and then run git clone again

![image](https://user-images.githubusercontent.com/69744247/208804481-6be31a62-8011-44f3-a27b-5e5d5e7d2788.png)










