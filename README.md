# VMAP XML generator for python        

```python
vmap = VMAP()
adBreak = vmap.attachAdBreak({
    "timeOffset": "00:00:05",
    "breakType": "linear"
})

adBreak.attachAdSource("VASTAdData", "<xml></xml>")
adBreak.attachEvent(event, "http://url.com")
print vmap.xml()
```
