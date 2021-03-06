## This is a module for [Magic Mirror](https://github.com/MichMich/MagicMirror)
### How to install
Clone this repo into your 'modules' folder

```bash
git clone https://github.com/shnopy/MMM-catfact.git
cd MMM-catfact
npm install
```

### How to use

```javascript
modules:[
   {
			module: 'MMM-catfact',
			position: 'top_left',
			config: {
				maxlength: 40,
				fadespeed: 2000,
				updatespeed: 10000,
				size: 'small'
			}
		},
]
```

|Option|Description|
|---|---|
|`maxlength`|`Integer` Sets how many characters can be in the fact. **Default: 40**|
|`fadespeed`|`Integer` Controls fade speed (`ms`). **Default: 2000**|
|`updatespeed`|`Integer` Controls how much time there is between facts (`ms`). **Default: 10000**|
|`size`|`String` Controls the size of the text. Options: ``xsmall, small, medium, large, xlarge`` **Default: small**|
