# Rol_kayıt.yag

<p>
	Belirlenen rolleri kullanıcılara verip almaya yarar.<br>
	Basit kayıt işlemleri için kullanılır.
</p>

<img src="../../assets/Moderasyon/Rol_kayıt/rol_kullanım.gif?raw=true" width="60%"/>

<p float="left">
	<img src="../../assets/Moderasyon/Rol_kayıt/rol_verme.png?raw=true" width="30%"/>
	<img src="../../assets/Moderasyon/Rol_kayıt/rol_alma.png?raw=true" width="30%"/>
</p>

<img src="../../assets/Moderasyon/Rol_kayıt/rol_hata.png?raw=true" width="60%"/>

## Kullanım Örnekleri

> [!NOTE]
> Prefix'inizin farklı olabileceğini unutmayın!

<p>
	Üye rolü verme: `-rol ver üye @Hazar`<br>
	Kız rolü alma: `-rol al kız 391247103839436800`<br>
	Erkek rolü verme: `-rol ver erkek @Hazar`
</p>

> [!NOTE]
> Kullanıcı ID yerine @etiket ile de çalışır!

## Kurulum & Gereksinimler

Trigger|Trigger Türü|Kod|Gereksinimler|Custom Command Ayarları
|---|---|---|:---:|:---:|
rol|Command|[rol_kayıt](rol_kayıt.yag)|[rol ID](https://github.com/hhhhh-ckr/yagpdb-cc-tr/blob/main/Moderasyon/README.md#:~:text=kendi%20rollerinizin%20ID%27leri)|Moderatör rollerine izin verin

> [!IMPORTANT]
> Kodun içindeki rol ID'leri kendi rollerinizin ID'leri ile değiştirmelisiniz!