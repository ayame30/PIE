Fix border-radius and background-size:cover in ie8

### PIE.htc Usage

```
zoom: 1;
position: relative;
-ms-behavior: url(/public/assets/js/common/plugins/lib/PIE.htc);
-pie-background: url('{{=img }}');
```
### selectivizr Usage

support :nth-of-type selector in IE 8

### Coding in ie8
```
width: 100%;
padding-left: 90px;
margin-left: -90px;
```
instead of
```
width: calc(100% - 90px);
```