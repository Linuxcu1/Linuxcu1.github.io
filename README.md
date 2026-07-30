### Kişisel Blog siteme hoş geldiniz! 
* Bu blog sitesi, **hugo** ile oluşturulmuş olup, tema olarak **congo** teması kullanılmıştır. 

### Kullanılan Teknolojiler
* **Site Üretici** =  [Hugo](https://github.com/gohugoio/hugo)
* **Tema** = [Congo](https://github.com/jpanther/congo)
* **Barındırma** = Github Pages (Github actions ile otomatik)

### Klasör yapısı 
```
📁 Linuxcu1.github.io  #Repo adı
| 
| 
|
|----> 📁 content/         #İçerikler                                 
|	    |---> 📁 en/       #Birden fazla dil desteği için dosya. (İngilizce)
|	    |---> 📁 tr/       #Birden fazla dil desteği için dosya. (Türkçe)
|----> 📁 assets/          #Resimler vb. buarada bulunur. 
|		|---> 📁 images/     
|----> 📁 config/
|		|---> 📁 _default/               #Config dosyaları burada bulunur.
|			  |---> 📄 hugo.toml 
|			  |---> 📄 languages.en.toml 	
|			  |---> 📄 languages.tr.toml 
|			  |---> 📄 menus.en.toml
|			  |---> 📄 menus.tr.toml 
|			  |---> 📄 markup.toml
|			  |---> 📄 module.toml 
|			  |---> 📄 params.toml 
|----> 📁 static/        #Faviconlar burada bulunur. 
|----> 📁 layouts/       # Varsa özel render-hook veya şablon özelleştirmeleri
```

### Proje'nin klonlanması

* **1.adım Git'in indirilmesi** 

	**Arch ve Arch tabanlılar için;**
	* Sudo pacman -S git  

	**Fedora;**
	* Sudo dnf install git 

	**Ubuntu & Debian**
	* Sudo apt install git 

* **2.adım Repo'nun klonlanması**

`git clone https://github.com/Linuxcu1/Linuxcu1.github.io.git` 

