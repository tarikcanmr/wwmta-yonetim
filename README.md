# **WildWorld MTA**
<h3>wwmta-yonetim scriptinin neleri düzenlenmelidir?</h3>
&nbsp; Script sitemizde bulunan <b>Sunucuya Mesaj Gönderme, Script Startlama, Script Stoplama</b>gibi işlevleri çalıştırabilmek için 


_**acl.xml**_'i düzenlemeniz gereklidir.Script'i indirdikten sonra <a href="https://github.com/tarikcanmr/wwmta-yonetim/blob/master/README.md#aclden-adminlik-nas%C4%B1l-verilir"> ACL üzerinden scripte adminlik</a> vermeniz gerekmektedir.

Daha sonrasında Script'in içindeki _**ayarlar.lua**_ dosyasını açıp websitemize giriş yaparken kullandığınız <a href="https://github.com/tarikcanmr/wwmta-yonetim/blob/master/README.md#ayarlarlua-nas%C4%B1l-d%C3%BCzenlenir"> _kullanıcı adı_ ve _şifrenizi_ ayarlar.lua dosyasına</a> girin.


<h6>ACL'den adminlik nasıl verilir?</h6>

> _mods\deathmatch klasöründe bulunan **acl** dosyasını düzenlemeniz gerekmektedir._ <br/>
> _**Admin** grubunu bulup içine aşağıdaki kodu ekleyin._

```xml
<object name="resource.wwmta-yonetim"></object>
```

<h6>ayarlar.lua nasıl düzenlenir?</h6>

> _mods\deathmatch\resources klasöründe bulunan **ayarlar.lua** dosyasını düzenlemeniz gerekmektedir._ <br/>
> _**Kullanıcı adı** ve **Şifre**'nin sırasını karıştırmayın._

```lua
hesaplar = {

  "kullaniciadi","sifre"

}
```

##### *© 2020 wildworldmta script version: v0.10*
