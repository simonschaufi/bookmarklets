# My personal bookmarklets

## TYPO3 Plugin list_type
```javascript
javascript:(function(){alert(document.getElementById('typo3-contentIframe').contentWindow.document.body.querySelector("[name*='list_type'] > option:checked").value);})()
```

## Instagram image download
```javascript
javascript:(function(){window.open(document.querySelector('html > body > div > div > div > div > article > div > div > div > div > img').src,'_blank');})();
```

## PredictHQ background image download
```javascript
javascript:(function(){window.location.href=document.querySelector('#background').style.backgroundImage.slice(5,-2);})();
```

## Hallooh full image download
```javascript
javascript:(function(){var src=document.querySelector('.profile-pic-similar .profile-pic').src;window.open(src.substring(0,src.indexOf('?'))+'?ixlib=php-1.1.0','_blank');})();
```

## Start XDEBUG in PhpStorm
```javascript
javascript:(function(){document.cookie='XDEBUG_SESSION='+'PHPSTORM'+';path=/;';})()
```

## Open TYPO3 Backend in new tab
```javascript
javascript:(function(){window.open(location.protocol+'//'+location.host+'/typo3/','_blank');})();
```

## NEW TEMPLATE
```javascript
javascript:(function(){CONTENTGOESHERE})();
```
