# sysdig

Installing step:

```
curl -s https://raw.githubusercontent.com/ajithreddygeth/sysdig/main/sysdig.sh | sudo bash
```

Verify:

```
$ sudo sysdig

7 14:42:57.166587229 0 sysdig (17847) > switch next=9 pgft_maj=0 pgft_min=1731 vm_size=54076 vm_rss=5196 vm_swap=0
8 14:42:57.166590905 0 <NA> (9) > switch next=6 pgft_maj=0 pgft_min=0 vm_size=0 vm_rss=0 vm_swap=0
9 14:42:57.166593672 0 <NA> (6) > switch next=0 pgft_maj=0 pgft_min=0 vm_size=0 vm_rss=0 vm_swap=0
10 14:42:57.167199885 0 <NA> (0) > switch next=17847(sysdig) pgft_maj=0 pgft_min=0 vm_size=0 vm_rss=0 vm_swap=0
45 14:42:57.167698775 0 sysdig (17847) > switch next=9 pgft_maj=0 pgft_min=1763 vm_size=54080 vm_rss=5264 vm_swap=0
46 14:42:57.167701465 0 <NA> (9) > switch next=6 pgft_maj=0 pgft_min=0 vm_size=0 vm_rss=0 vm_swap=0

```
