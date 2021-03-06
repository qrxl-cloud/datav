---
keyword: 发布PC端可视化应用
---

# 发布PC端可视化应用

本文档介绍如何发布一个PC端可视化应用。通过PC端可视化应用的发布功能，可以将已经开发完成的PC端可视化应用发布到线上环境，并进行访问权限的设置，供其他人员在线观看。

1.  登录[DataV控制台](https://datav.aliyun.com/)。

2.  在**我的可视化**页面中，选择一个可视化应用，单击**编辑**。

3.  在PC端画布编辑器中，单击页面右上角的**发布**图标。

    ![发布按键](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5495541061/p80851.png)

4.  在**发布**对话框中，单击**发布大屏**。

    ![发布大屏](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5992634951/p80847.png)

    **说明：** 如果是首次发布可视化应用，系统会弹出**发布成功**的对话框，在对话框中您可以单击**前往快照管理**查看快照，如果无需查看请单击**取消**进入发布页面。

    ![前往移动端快照管理](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/1331379951/p149131.png)

5.  发布成功后，系统会开启**已发布**开关，并生成分享链接和二维码。单击**二维码**可展示当前可视化应用的二维码，扫描该二维码即可在线访问您的可视化应用。

    ![二维码](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/1992634951/p130792.png)

6.  在线访问您的PC端可视化应用。

    单击**分享链接**右侧的**复制**图标，打开浏览器，将复制的链接粘贴到地址栏中，即可在线访问您的PC端可视化应用。

    ![发布界面](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/1356903061/p149128.png)

    **说明：** 可视化应用项目发布后，如果您想更换分享链接，可单击**分享链接**右侧的![重新生成链接](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5992634951/p93475.png)（**重新生成链接**）图标，重新生成一个**分享链接**。重新生成后，旧的分享链接将不可用，请使用新的分享链接访问目标可视化应用。

    可视化应用分享成功后，您可以配置[发布快照](#section_cby_xj7_wbn)的参数内容，还可以进行[访问限制](#section_8hf_4c4_xj7)[分享信息](#section_chx_nee_p1h)和[加载页设置](#section_0d9_wex_all)的配置。

    **说明：** 为了更好地支持分享，DataV可视化应用分享页域名即将从datav.aliyun.com/share/example切换为datav.aliyuncs.com/share/example，此变更可能对您的DataV可视化应用项目造成的影响，对您造成的不便敬请谅解。请参见[DataV发布分享页域名变更问题](/cn.zh-CN/常见问题/DataV发布分享页域名变更问题.md)及时排查并解决可能存在的问题。


## 发布快照

设置分享链接后，可以配置**发布快照**，指定访问者看到的可视化应用版本（默认为快照发布版本）。屏幕的内容会锁定在快照创建的那一刻。

**说明：** 存档之后，屏幕内容的编辑和修改不会同步到历史快照中，可作为稳定预览版本的备份。

具体操作方式如下。

1.  在**发布**对话框中，在**发布快照**列表中，选择一个已存档的历史快照即可完成该历史快照的发布。

    -   如果当前可视化应用没有历史快照，系统会将当前编辑器的内容作为第一个快照进行发布。
    -   如果当前可视化应用有历史快照，系统会自动发布最新一条快照。
2.  单击下方**覆盖已发布快照**，把已发布快照内的可视化应用的内容变成当前编辑页下的内容。

3.  单击下方**自动新增快照并发布**，自动新增一个快照并选中新增的快照后立刻发布。

4.  单击下发**管理快照**，可在管理快照界面管理多个历史快照，详情请参见[快照管理](#section_b4t_5lo_6co)。


## 快照管理

单击**发布**对话框内的**管理快照**，或者您也可以单击可视化应用编辑器右上角**生成快照**右侧的**管理快照**图标（![管理快照下拉框](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5992634951/p80875.png)），然后在**快照管理**对话框内可进行如下快照管理操作。

-   **查看额度**：在**快照管理**对话框右上角可以查看管理快照界面内剩余可创建快照的额度。一旦快照数量达到上限后无法新增快照，需要删除不需要的快照。

    **说明：** 企业版用户有3个快照额度，专业版用户有10个快照额度。

-   **新增快照**：在**快照管理**对话框中单击**新增快照**即可新增一个历史快照。
-   **覆盖已发布快照**：单击**覆盖已发布快照**，编辑器的内容覆盖发布页快照原有的内容，即更新发布页内容，并且实时生效。更新内容包括画布编辑器配置、数据源配置、蓝图编辑器配置。

    ![覆盖快照](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5992634951/p80871.png)

-   **发布或关闭快照**：选中管理栏内某个历史快照，单击右侧![发布快照](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5992634951/p80867.png)图标可快捷发布可视化应用或切换发布的快照，切换后，发布页内容将切换成对应快照的内容，再次单击图标即可关闭快照。

    **说明：** 已发布的快照无法被删除。

-   **锁定快照**：单击某个历史快照右侧的![锁定快照](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5992634951/p80869.png)图标即可锁定快照，快照锁定后，不可删除和覆盖。
-   **批量删除**：在管理界面内多选或全选快照后，单击下方**批量删除**图标可进行快照批量删除。批量删除功能无法删除已发布和被锁定的快照。

    ![批量删除](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5992634951/p80870.png)

    **警告：** 快照目前仅支持切换，不具备回滚的功能，删除后将无法恢复，请谨慎操作。

-   **注释快照**：可单击![编辑注释](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5992634951/p96282.png)图标，自定义添加快照的注释内容。

    ![注释图标](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5992634951/p80872.png)


## 访问限制

DataV的发布功能提供了四种分享可视化应用的方式：

-   公开分享（默认）。
-   [密码访问](#section_8wu_qtp_9a7)分享。
-   [通过Token验证](#section_wfx_iph_pfi)分享。
-   [IP白名单访问](#section_wve_w73_s3g)分享。

**说明：** 仅企业版及以上版本支持**访问限制**功能。

## 密码访问

1.  在**发布**对话框中，打开**访问密码**。

    ![DataV访问密码配置](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/2356903061/p65194.png)

2.  在**访问密码**输入框中，输入您的验证密码。

    密码长度为6位以上，且必须具备以下三个条件：

    -   至少包含一个英文大写字母A～Z。
    -   至少包含一个英文小写字母a～z。
    -   至少包含一个数字0～9。
    密码设置成功后，系统会提示**已设置访问限制**。

3.  配置**验证有效期**。

    **说明：** 只有密码设置成功或开启Token验证后，才可配置**验证有效期**。

    -   勾选**验证有效期**，可以设置密码的有效期，最长为32小时。访问者首次输入密码且成功访问可视化应用后，在设置的有效期时间内，可任意访问该可视化应用而无需输入密码。
    -   去勾选**验证有效期**，每次访问都需要输入密码。
    密码设置成功后，当您再次访问可视化应用的分享链接时，系统会提示需要输入密码。

    ![密码访问大屏页面](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5992634951/p8033.png)


## 通过Token验证

您可以通过Token验证的方式，将可视化应用的访问权限与您的权限体系进行集成。

在**发布**对话框中，打开**通过Token验证**开关，即可开启Token验证。Token验证开启后，您可进行如下操作：

-   （可选）配置**验证有效期**。
    -   勾选**验证有效期**，可自定义调整Token验证的有效期，最长设置为32小时。访问者首次进行Token验证并成功访问可视化应用后，在设置的有效期时间内，可任意访问该可视化应用而无需再次进行验证。

        ![设置TOKEN有效期限](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/2356903061/p103580.png)

    -   去勾选**验证有效期**，每次访问都需要通过验证。
-   获取Token验证码。

    打开**通过Token验证**开关后，DataV会生成一个Token，如下图所示。您需要记录这个Token，以备后用。

    ![获取Token验证码](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/5992634951/p80866.png)


Token验证开启后，再次打开可视化应用的分享页面，会收到一个**Access Denied**消息，表示您的访问被拒绝了。如果想要打开您的页面，需要完成以下步骤。

**说明：** 为了防止重放攻击，请确保您的服务器时间为东8区标准时间。DataV只会提供1分钟的误差，如果时间误差超过1分钟将会验证失败。

1.  发布可视化应用，记录可视化应用编码（URL的最后一段）。

2.  将编码与当前时间（毫秒）连起来，并用 \|（竖线）分隔开。

3.  使用Token通过HMAC-SHA256 base64，对上一步得到的Token验证码进行加密。

4.  将时间和加密后的签名分别命名为`_datav_time`、`_datav_signature`。

5.  将它们依次放入`url` 的querystring中。

    **说明：** 如果您的可视化应用URL中需要使用Get的方式传递参数，为了安全性，建议您使用DataV提供的Token参数签名校验，详情请参见[DataV分享页Token参数签名校验](/cn.zh-CN/可视化应用管理/DataV分享页Token参数签名校验.md)。

    示例代码如下：

    -   PHP：

        ```
        <?php
          $token = "kBwoX9rFX9v4zbOT0Gjd_wr65DZ****";
          $screenID = "03d1b68faeb09671046d1ef43f58****";
          $time = time()*1000;
          $stringToSign = $screenID.'|'.$time;
          $signature = urlencode(base64_encode(hash_hmac('sha256', $stringToSign, $token, true)));
          $url = "http://datav.aliyuncs.com/share/".$screenID."?_datav_time=".$time."&_datav_signature=".$signature;
        ?>
        <iframe width=100% height=100% src="<?=$url?>"/>
        ```

    -   Node.js：

        ```
        const crypto = require('crypto');
        var token = "Ev97wOUSAtJusc3Vsd9O2ngr_vfV****";
        var screenID ="14c5448c00ecde02b065c231d165****";
        var time = Date.now();
        var stringToSign = screenID +'|'+ time;
        var signature = crypto.createHmac('sha256', token).update(str).digest().toString('base64');
        var url="http://datav.aliyuncs.com/share/"+ screenID +"?_datav_time="+time+"&_datav_signature="+ encodeURIComponent(signature);
        ```

    -   Java：

        ```
        package com.company;
        import java.security.*;
        import java.util.Date;
        import javax.crypto.*;
        import javax.crypto.spec.SecretKeySpec;
        import org.apache.commons.codec.binary.Base64;
        import java.net.URLEncoder;
        public class TokenTest {
            public static String getSignedUrl(String screenID, String token){
                Date date = new Date();
                Long time = date.getTime();
                String stringToSign = screenID + "|" + time;
                String signature = HMACSHA256(stringToSign.getBytes(), token.getBytes());
                String url = "http://datav.aliyuncs.com/share/"+ screenID +"?_datav_time="+time+"&_datav_signature="+ signature;
                return url;
            }
            /**
             *  使用java原生的摘要实现SHA256加密。
             * @param str加密后的报文。
             * @return
             */
            public static String HMACSHA256(byte[] data, byte[] key)
            {
                try  {
                    SecretKeySpec signingKey = new SecretKeySpec(key, "HmacSHA256");
                    Mac mac = Mac.getInstance("HmacSHA256");
                    mac.init(signingKey);
                    return URLEncoder.encode(byte2Base64(mac.doFinal(data)));
                } catch (NoSuchAlgorithmException e) {
                    e.printStackTrace();
                } catch (InvalidKeyException e) {
                    e.printStackTrace();
                }
                return null;
            }
            private static String byte2Base64(byte[] bytes){
                return Base64.encodeBase64String(bytes);
            }
            public static void main(String[] args) throws Exception {
                System.out.println(getSignedUrl("screenId", "token"));
            }
        }
        ```

    -   C\#：

        ```
        using System;
        using System.Security.Cryptography;
        using System.Text.RegularExpressions;
        using System.Collections.Generic;
        using System.Linq;
        using System.Web;
        using System.Text;
        
        namespace datavToken
        {
            class Program
            {
                static void Main(string[] args)
                {
                    var dic = new Dictionary<string, string>();  // 自定义参数。
                    dic.Add("datav_sign_no", "123998");         // datav_sign_开头，需要签名。
                    dic.Add("datav_sign_lo", "kk");
                    dic.Add("datav_sign_ao", "xx");
        
                    dic.Add("name", "123");   // 不需要签名。
                    // 分享页前缀，屏幕分享id、token，自定义参数字典。
                    Console.WriteLine(GenerateUrl("https://datav.aliyun.com/share/", "ca74bea5e45503070d607795e0****", "66DsL2qjrXRHluSJScv_flOUhn****", dic));
                }
                private static string GenerateUrl(string datavBase, string screenId, string token, Dictionary<string, string> customeParams)
                {
                    string pattern = @"^datav_sign_.*";
                    string timestamp = GetTimeStamp();
        
                    // 参数排序。
                    Dictionary<string, string>.KeyCollection keyCol = customeParams.Keys;
                    List<string> signKeys = new List<string>();
        
                    foreach (var item in keyCol.ToList())
                    {
                        if (Regex.IsMatch(item, pattern))
                        {
                            signKeys.Add(item);
                        }
                    }
        
                    // 按照key排序。
                    signKeys = signKeys.OrderBy(k => k).ToList();
        
                    string paramsSignStr = signKeys.Aggregate("", (total, key) =>
                    {
                        if (total != "")
                        {
                            total += "&";
                        }
                        total += key + "=" + customeParams[key];
                        return total;
                    });
        
                    string signStr = screenId + "|" + timestamp + "|" + paramsSignStr;
        
                    var encoding = new System.Text.ASCIIEncoding();
                    byte[] keyByte = encoding.GetBytes(token);
                    byte[] messageBytes = encoding.GetBytes(signStr);
                    string signature;
                    using (var hmacsha256 = new HMACSHA256(keyByte))
                    {
                        byte[] hashmessage = hmacsha256.ComputeHash(messageBytes);
                        signature = Convert.ToBase64String(hashmessage);
                    }
        
        
                    var paramDic = new Dictionary<string, string>();
                    paramDic.Add("_datav_time", timestamp);
                    paramDic.Add("_datav_signature", signature);
        
                    foreach (var item in customeParams)
                    {
                        paramDic.Add(item.Key, item.Value);
                    }
                    return datavBase + screenId + "?" + ParseToString(paramDic);
                }
                public static string GetTimeStamp()
                {
                    TimeSpan ts = DateTime.UtcNow - new DateTime(1970, 1, 1, 0, 0, 0, 0);
                    return Convert.ToInt64(ts.TotalMilliseconds).ToString();
                }
                static public string ParseToString(IDictionary<string, string> parameters)
                {
                    IDictionary<string, string> sortedParams = new SortedDictionary<string, string>(parameters);
                    IEnumerator<KeyValuePair<string, string>> dem = sortedParams.GetEnumerator();
        
                    StringBuilder query = new StringBuilder("");
                    while (dem.MoveNext())
                    {
                        string key = dem.Current.Key;
                        string value = dem.Current.Value;
                        if (!string.IsNullOrEmpty(key) && !string.IsNullOrEmpty(value))
                        {
                            query.Append(key).Append("=").Append(HttpUtility.UrlEncode(value)).Append("&");
                        }
                    }
                    string content = query.ToString().Substring(0, query.Length - 1);
        
                    return content;
                }
            }
        }
        ```


## IP白名单访问

1.  在**发布**对话框中，打开**IP白名单**。

    ![IP白名单限制](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/6112813061/p174531.png)

2.  在下方**IP白名单**输入框中，输入您的IP，并用“,“号分隔不同的白名单。

    **说明：** 设置启用IP白名单后，发布后的可视化应用仅允许在设置范围内的白名单IP下访问。

    IP白名单设置成功后，当您再次访问可视化应用的分享链接时，如果您使用了非白名单IP访问当前可视化应用，可视化应用页面访问将被拒绝。

    ![访问拒绝](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/zh-CN/6112813061/p174535.png)


## 分享信息

DataV可视化应用在分享发布链接时能提供了可自定义修改分享信息内容的功能，详细参数配置介绍如下。

![分享信息配置内容举例](../images/p164696.png "分享信息配置内容样例")

![分享链接样例展示](../images/p164697.png "分享链接样例展示")

|配置参数|说明|
|----|--|
|**标题**|您可以自定义修改即将发布的可视化应用分享链接的标题名称，默认显示为创建该可视化应用时的标题名。|
|**描述**|您可以对即将发布的可视化应用分享链接进行简单的内容描述。|
|**图片**|您可以对即将发布的可视化应用，通过自定义输入图片URL链接或拖动本地图片到右侧图片栏内，为分享链接设置一张图片。|

## 加载页设置

DataV可视化应用在分享发布链接时能提供了可自定义设置加载页内容的功能，详细参数配置介绍如下。

**说明：** 仅专业版及以上版本支持**加载页配置**功能。

![加载页案例](../images/p174550.jpg "加载页配置内容样例")

![加载页展示](../images/p174557.png "加载页样例展示")

|配置参数|说明|
|----|--|
|**背景**|您可以自定义修改即将发布的可视化应用加载页的背景颜色，支持纯色及渐变色。|
|**Logo**|您可以对即将发布的可视化应用加载页的Logo图片，通过自定义输入图片URL链接或拖动本地图片到右侧图片栏内，为Logo设置一张图片。|

## 常见问题

已经**实时发布**的可视化应用如何迁移？

-   没有在首页或编辑页单击**发布**按钮的可视化应用，保持实时发布。
-   需要变更发布的可视化应用，单击进入发布页之前，会对当前在编辑可视化应用自动打快照。跳转发布页后，选择快照，即可完成**快照发布**。

