# 图片来源与校验报告 · image_report.md

交付物:`output/brand_positioning.html` / `output/brand_positioning.png`(女装品牌定位 单页)

## 校验方法

1. **来源**:DuckDuckGo 图片搜索(ddgs / DDG i.js API),按任务指定的检索词抓取,浏览器 UA + 每次下载间隔 1s。
2. **自动校验**:PIL 可正常打开、短边 ≥400px、宽高比 1:2–2:1、文件 >20KB;同品牌内容去重。
3. **品牌匹配**:5 个 SHEIN 子品牌要求品牌名出现在搜索结果标题或来源 URL 中;7 个竞品优先保留品牌自有域名结果。
4. **视觉复核**:12 个并行视觉校验(每品牌一个),逐图检查产品类型、是否为可用于 deck 的干净商品图、有无异品牌水印、标题与来源 URL 的一致性;不合格图片已剔除并在下方注明。

## 总览

| 品牌 | 类型 | 使用图片数 | 旗标 |
|---|---|---|---|
| Uniqlo | 竞品 | 2 | **CONFIDENT** |
| Everlane | 竞品 | 3 | **CONFIDENT** |
| COS | 竞品 | 3 | **CONFIDENT** |
| Zara | 竞品 | 3 | **CONFIDENT** |
| Princess Polly | 竞品 | 3 | **CONFIDENT** |
| Free People | 竞品 | 2 | **CONFIDENT** |
| House of CB | 竞品 | 3 | **CONFIDENT** |
| Enliva | SHEIN 子品牌 | 2 | **CONFIDENT** |
| ENCHNT | SHEIN 子品牌 | 2 | **CONFIDENT** |
| Anewsta | SHEIN 子品牌 | 3 | **CONFIDENT** |
| BELROSIE | SHEIN 子品牌 | 3 | **NEEDS REVIEW** |
| MOTF | SHEIN 子品牌 | 3 | **CONFIDENT** |

## 分品牌明细

### Uniqlo — **CONFIDENT**

- `uniqlo_3.jpg`
  - 图片 URL:https://www.uniqlo.com/jp/ja/contents/feature/masterpiece/common/au/img/product/item_05_03_02.jpg?240829
  - 来源页面:https://www.uniqlo.com/au/en/contents/feature/masterpiece/product/supima-cotton-crew-neck-t-shirt/
- `uniqlo_4.jpg`
  - 图片 URL:https://image.uniqlo.com/UQ/ST3/jp/imagesother/t-shirts/img/women/supima_mv01.jpg?20220222
  - 来源页面:https://www.uniqlo.com/in/en/special-feature/t-shirts-women

全部图片来自 uniqlo.com 核心 SUPIMA 棉 T 恤(LifeWear 基础线)。首轮抓取的 2 张模特图因带有「UNIQLO U」设计师支线标志(不符合“仅核心基础款”要求)被人工替换为核心线图片。

### Everlane — **CONFIDENT**

- `everlane_1.jpg`
  - 图片 URL:https://media.everlane.com/image/upload/c_fill,dpr_1.0,f_auto,g_face:center,q_auto,w_auto/v1/i/22ded1b5_4e2b.jpg
  - 来源页面:https://www.everlane.com/
- `everlane_2.jpg`
  - 图片 URL:https://media.everlane.com/image/upload/c_fill,dpr_1.0,f_auto,g_face:center,q_auto,w_auto/v1/i/22ded1b5_7588.jpg
  - 来源页面:https://www.everlane.com/
- `everlane_3.jpg`
  - 图片 URL:https://media.everlane.com/images/c_fill,w_3840,ar_4:5,q_auto,dpr_1.0,f_auto,fl_progressive:steep/i/ab4e49ac_2e87/womens-twill-utility-straight-leg-pant-black
  - 来源页面:https://www.everlane.com/products/womens-organic-straight-leg-pant-black

3 张图片均来自 everlane.com 官方 CDN(media.everlane.com),视觉校验通过。

### COS — **CONFIDENT**

- `cos_1.jpg`
  - 图片 URL:https://media.cos.com/assets/001/ea/b4/eab463e7846ec0d9d147f117a50e0a58105843f2_xxl-1.jpg?imwidth=2160
  - 来源页面:https://www.cos.com/en-us/women/womenswear/dresses/jerseydresses/product/sculpted-cotton-midi-dress-navy-1275075005
- `cos_2.jpg`
  - 图片 URL:https://media.cos.com/assets/001/f0/b3/f0b3fcf2171c4d43ae0aa3cb721b77d1d4a0ed26_xxl-1.jpg?imwidth=1200
  - 来源页面:https://www.cos.com/en-eu/women/womenswear/dresses/mididresses/product/ruffled-draped-midi-dress-black-1326232002
- `cos_3.jpg`
  - 图片 URL:https://d.fashiontimes.com/en/full/51486/cos-pleated-line-mini-dress.jpg?w=768&f=b3512f3ee6404fd641b6fa4eac59d803
  - 来源页面:https://www.fashiontimes.com/why-cos-fashion-brand-has-become-go-minimalist-clothing-modern-wardrobe-essentials-13558

前 2 张来自 cos.com 官方商品页;第 3 张来自时尚编辑网站(fashiontimes.com)但为 COS 官方商品摄影风格,视觉校验确认为 COS 产品。

### Zara — **CONFIDENT**

- `zara_1.jpg`
  - 图片 URL:https://static.zara.net/photos/2023/V/0/1/p/5598/022/330/2/w/1366/5598022330_2_1_1.jpg?ts=1676026249464
  - 来源页面:https://wear-next.com/trends/zara-summer-dresses-collection-uk/
- `zara_2.jpg`
  - 图片 URL:https://static.zara.net/photos/2023/V/0/1/p/9878/102/098/3/w/1366/9878102098_1_1_1.jpg?ts=1676039065824
  - 来源页面:https://wear-next.com/trends/zara-summer-dresses-collection-uk/
- `zara_3.jpg`
  - 图片 URL:https://i.pinimg.com/originals/5a/22/36/5a223611027e0946231d93e18f34b775.jpg
  - 来源页面:https://ca.pinterest.com/pin/floral-print-dress-new-inwoman--381469030936351703/

前 2 张直接来自 Zara 官方 CDN(static.zara.net);第 3 张为 Pinterest 转载的 Zara 官方商品图(标题与 pin 链接均指向 Zara 商品页),视觉校验通过。

### Princess Polly — **CONFIDENT**

- `princesspolly_1.jpg`
  - 图片 URL:https://us.princesspolly.com/cdn/shop/files/1-modelinfo-elly-us2_88232f8f-cadf-45e0-8c2c-fb91f6d768d3_1024x1024.jpg?v=1710915476
  - 来源页面:https://us.princesspolly.com/products/bombshell-mini-dress-white
- `princesspolly_2.jpg`
  - 图片 URL:http://us.princesspolly.com/cdn/shop/files/1-modelinfo-elise-us2_fc0fe929-c0e9-481d-84b2-0250816361e2_1024x1024.jpg?v=1706848688
  - 来源页面:https://us.princesspolly.com/products/lanchester-mini-dress-white
- `princesspolly_3.jpg`
  - 图片 URL:http://us.princesspolly.com/cdn/shop/products/2-modelinfo-elly-us2_705edd36-d69c-45db-bfec-6832fd03d549_1024x1024.jpg?v=1667952524
  - 来源页面:https://us.princesspolly.com/products/kenzie-mini-dress-pink

3 张图片均来自 us.princesspolly.com 官方商品页,视觉校验通过。

### Free People — **CONFIDENT**

- `freepeople_own_1.jpg`
  - 图片 URL:https://images.urbndata.com/is/image/FreePeople/49957004_411_a?$cat-tile-preset$
  - 来源页面:https://www.freepeople.com/boho-dresses/
- `freepeople_own_3.jpg`
  - 图片 URL:https://images.ctfassets.net/udk41sh7kfzj/7HOHpDiZXxdOrIGw3JcTfw/e610c396b32b915413b2fe851b0c7060/4UPTopper_Printed.jpg?w=690&q=80&fm=jpg&fl=progressive
  - 来源页面:https://www.freepeople.com/dresses/
- ~~`freepeople_own_2.jpg`~~(已剔除,未用于页面)
  - 图片 URL:https://img1.fpassets.com/is/image/FreePeople/39573076_066_0?$pdp$
  - 来源页面:https://www.freepeople.com/shop/folk-town-boho-dress-39573076/

首轮通用搜索无官网结果,已用 site:freepeople.com 定向检索替换;保留的 2 张均来自 freepeople.com(URBN/fpassets/ctfassets 为其官方图片 CDN)。第 3 张(Spell & the Gypsy Collective,Free People 平台上的第三方品牌)经视觉校验后剔除。

### House of CB — **CONFIDENT**

- `houseofcb_1.jpg`
  - 图片 URL:https://d166chel5lrjm5.cloudfront.net/images/detailed/104/persephone-pg-1.jpg
  - 来源页面:https://www.houseofcb.com/persephone-smoke-strapless-corset-dress-us.html
- `houseofcb_2.jpg`
  - 图片 URL:https://d166chel5lrjm5.cloudfront.net/images/detailed/99/004481.jpg
  - 来源页面:https://www.houseofcb.com/pietra-french-navy-corset-mini-dress.html
- `houseofcb_3.jpg`
  - 图片 URL:https://d166chel5lrjm5.cloudfront.net/images/detailed/104/samaria-3.jpg
  - 来源页面:https://www.houseofcb.com/samaria-ballerina-pink-corset-sundress.html

3 张图片的来源页均为 houseofcb.com 官方商品页(图片 CDN 为其 CloudFront 域),视觉校验通过。

### Enliva — **CONFIDENT**

- `enliva_1.jpg`
  - 图片 URL:https://img.ltwebstatic.com/v4/j/pi/2025/12/05/d6/17649192741942dba1a12d7080d057ab3955057740_thumbnail_900x.webp
  - 来源页面:https://us.shein.com/Enliva-Ry2ky-Plus-Size-Vintage-Corduroy-Embroidered-Floral-Pinafore-Dress-Summer-For-Apple-Rounded-Body-Shape-p-139550418.html
- `enliva_2.jpg`
  - 图片 URL:https://img.ltwebstatic.com/images3_pi/2023/11/10/dd/1699588383cfaf5be5abbaa1ed9ca2ef276c6f839f_thumbnail_900x.webp
  - 来源页面:https://es.shein.com/Enliva-Plus-Size-V-Neck-Lantern-Sleeve-Belted-Dress-p-282495933.html
- ~~`enliva_3.jpg`~~(已剔除,未用于页面)
  - 图片 URL:https://img.ltwebstatic.com/v4/j/spmp/2025/05/16/8b/17473804378619df66065acb661f79377f2a2310ff_wk_1747620190_thumbnail_900x.webp
  - 来源页面:https://us.shein.com/Plus-Size-Women-Faux-Pearl-Decor-Off-Shoulder-Long-Sleeve-Split-Hem-Elegant-Dress-Maxi-Women-Outfit-p-71433122.html

2 张保留图片的标题与 shein.com 商品页 slug 均含 Enliva,视觉校验确认(图内含 Enliva 水印)。第 3 张因是信息图式拼图(品牌正确但不适合放入 deck)被剔除。注意:enliva_1 左侧含 SHEIN 商品页常见的版型示意标注,如需更干净的图可人工替换。

### ENCHNT — **CONFIDENT**

- `enchnt_1.jpg`
  - 图片 URL:https://img.ltwebstatic.com/images3_pi/2024/07/15/47/17210129616bc08b2b4554fb6ea487bd0bf36919a6_wk_shein_thumbnail_900x.jpg
  - 来源页面:https://www.shein.co.uk/Enchnt-Summer-Holiday-Romantic-Elegant-White-Women-Summer-Elegant-3D-Ruffle-Strap-Midi-Dress-p-38655673.html
- `enchnt_2.jpg`
  - 图片 URL:https://img.ltwebstatic.com/images3_pi/2024/03/20/a1/1710919834f34d2ead78aedc9d119153204749343f_thumbnail_900x.webp
  - 来源页面:https://us.shein.com/Enchnt-Women-s-Summer-Spring-Holiday-White-Sundress-Hollow-Out-Embroidery-Off-Shoulder-Neckline-Ruffle-Trimmed-Romantic-Dress-With-Tassel-Tie-p-31805102.html
- ~~`enchnt_3.jpg`~~(已剔除,未用于页面)
  - 图片 URL:https://img.ltwebstatic.com/images3_pi/2024/07/24/14/17218170414bcae98214d3c5027a43ece79a489725_thumbnail_900x.jpg
  - 来源页面:https://www.shein.co.uk/Romantic-Fall-Holiday-Elegant-Pink-Neckline-Lantern-Sleeves-Ruffled-Waist-Bow-Dress-p-39348370-cat-1727.html?url_from=web_ukpin_dpa_women_sz2404295869769911

2 张保留图片的标题与 shein 商品页 slug 均含 Enchnt,视觉校验通过(仅含 SHEIN 自有水印)。第 3 张因商品页 slug 不含品牌名(仅标题含)被保守剔除。

### Anewsta — **CONFIDENT**

- `anewsta_1.jpg`
  - 图片 URL:https://img.ltwebstatic.com/v4/j/pi/2025/06/09/fe/1749434261c07e5cf30488642aa8be27c169ee8a5c_thumbnail_900x.webp
  - 来源页面:https://us.shein.com/Anewsta-Women-s-Long-Gray-Green-Pleated-Waist-Shiny-Elegant-Versatile-Dress-Spring-Autumn-p-95858581.html
- `anewsta_2.jpg`
  - 图片 URL:https://img.ltwebstatic.com/v4/j/pi/2025/06/06/4d/17492248243aa71eede42948391d7b961538a4ccb9_thumbnail_900x.webp
  - 来源页面:https://us.shein.com/Anewsta-Women-s-Elegant-Palace-Style-Puff-Sleeve-Waist-Cinched-Loose-Hem-Dress-Blue-p-94106353.html
- `anewsta_3.jpg`
  - 图片 URL:https://img.ltwebstatic.com/v4/j/pi/2026/01/19/92/1768788561df060e365e67194df14ec908b6353ef0_thumbnail_900x.webp
  - 来源页面:https://us.shein.com/Anewsta-Women-s-Elegant-V-Neck-Flare-Waist-Tie-Floral-Sleeve-Mesh-Party-Dress-Spring-Summer-p-374214272.html

3 张图片的标题与 us.shein.com 商品页 slug 均含 Anewsta,视觉校验通过。

### BELROSIE — **NEEDS REVIEW**

- `belrosie_1.jpg`
  - 图片 URL:https://img.ltwebstatic.com/v4/j/pi/2025/05/19/be/174763829077299fa2045e68051d634d59fabfdb17_thumbnail_900x.webp
  - 来源页面:https://us.shein.com/Aveloria-Rosie-French-Romantic-3D-Rose-V-Neck-Puff-Sleeve-Waist-Fitted-Extra-Long-Women-Dress-p-80826327.html
- `belrosie_2.jpg`
  - 图片 URL:https://img.ltwebstatic.com/v4/j/pi/2025/06/10/53/1749524228ea43400cfc3700f0baa6b989d9ed1e25_thumbnail_600x.jpg
  - 来源页面:https://www.shein.co.uk/store/home?store_code=8292205500&tab=items
- `belrosie_3.jpg`
  - 图片 URL:https://img.ltwebstatic.com/v4/j/pi/2025/09/22/d1/1758510879b816a387afa3ec1ead13ba6ac8ba67ed_thumbnail_900x.webp
  - 来源页面:https://us.shein.com/Aveloria-Rosie-New-Romantic-Vintage-French-Tea-Dress-Loose-Flattering-Design-Elegant-Off-Shoulder-Ruched-Sheer-Linen-Look-Puff-Sleeve-Solid-Color-Dress-For-Summer-p-189412563.html?mallCode=1&main_attr=27_513

belrosie_2 来自 SHEIN UK 的 BELROSIE 品牌店铺页,可信。但 belrosie_1 与 belrosie_3 的搜索标题为 BELROSIE、商品页 slug 却是「Aveloria-Rosie」——疑似同一店铺改名/换标(风格一致、同属 SHEIN),无法排除是相邻姊妹品牌,建议人工确认后再定稿。

### MOTF — **CONFIDENT**

- `motf_1.jpg`
  - 图片 URL:https://img.ltwebstatic.com/images3_pi/2022/07/14/16577732435ab8a81c241cbc3ccdf90aa67ec97c57_thumbnail_600x.jpg
  - 来源页面:https://us.shein.com/MOTF-PREMIUM-LINEN-BELTED-DRESS-p-11043172-cat-1727.html
- `motf_2.jpg`
  - 图片 URL:https://img.ltwebstatic.com/images3_pi/2025/01/20/f1/1737383638a9bc96caaf9ebab27bafef10cd1d7636_thumbnail_900x.webp
  - 来源页面:https://us.shein.com/MOTF-PREMIUM-BOW-DECOR-A-LINE-DRESS-p-54225559.html
- `motf_3.jpg`
  - 图片 URL:https://img.ltwebstatic.com/images3_pi/2023/06/19/1687180838d5676a6d74ad190576cf5b2ef0c65a82_thumbnail_900x.webp
  - 来源页面:https://us.shein.com/PREMIUM-FLORAL-PLEATED-MIDI-DRESS-p-18089499-cat-1727.html

3 张图片标题均为「MOTF PREMIUM …| SHEIN」且来自 us.shein.com 商品页(motf_3 的 slug 缺品牌前缀但标题含 MOTF),视觉校验通过。
