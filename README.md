Sample [Wercker](http://wercker.com/) box & step for golang
====

[![wercker status](https://app.wercker.com/status/a4d57dfaa497d9d433def27a8392980d/m "wercker status")](https://app.wercker.com/project/bykey/a4d57dfaa497d9d433def27a8392980d)

This is sample project to use wecker box and step for golang. 

## Box

- [tcnksm/wercker-box-gox](https://github.com/tcnksm/wercker-box-gox) - Wercker box for mitchellh/gox, cross-compiling golang project parallelly


## Step

### Build

- [tcnksm/wercker-step-goveralls](https://github.com/tcnksm/wercker-step-goveralls) - Wercker step for mattn/goveralls, integrate with coveralls.io 
- [tcnksm/wercker-step-gox](https://github.com/tcnksm/wercker-step-gox) - Wercker step for mitchellh/gox, cross-compiling golang project
- [tcnksm/wercker-step-zip](https://github.com/tcnksm/wercker-step-zip) - Wercker step for packaging directories

### Deploy

- [tcnksm/wercker-step-ghr](https://github.com/tcnksm/wercker-step-ghr) - Wercker step for tcnksm/ghr, create Github Release and uploading artifacts

