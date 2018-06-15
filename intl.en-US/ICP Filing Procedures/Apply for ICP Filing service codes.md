# Apply for ICP Filing service codes {#concept_z4d_drl_zdb .concept}

ICP Filing service codes are used to verify your Alibaba Cloud ECS instances.

## Restrictions {#section_r52_sm1_12b .section}

-   Requirements for servers: The region of your ECS instance must be in mainland China, the ECS instance must have at least a 3-month subscription, and you must have bought Internet bandwidth. If you did not buy Internet bandwidth when buying the ECS instance,  see the instructions in [Upgrade/Downgrade Configurations](https://www.alibabacloud.com/help/zh/doc-detail/25437.htm) to buy Internet bandwidth.

    **Note:** The Alibaba Cloud ICP Filing system does not support Pay-As-You-Go instances.

-   Number limit: You can apply for at most 5 filing service codes for an ECS instance.
-   One service code can only be used once: When a filing service code is used, it becomes permanently invalid after the filing is completed. The code can neither be used for the filing of another website domain name, nor be released or deleted for reuse.

## Procedure {#section_c3r_j3z_zdb .section}

1.  Log on to the  [Alibaba Cloud ICP Filing Management](https://bsn.console.aliyun.com/#/bsnApply/ecs) console using the account with which you purchase the Alibaba Cloud ECS instance. On the ICP Filing Management, click **ICP No. Application** from the drop-down box.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14195/5697_en-US.png)

2.  In the instance list, locate the instance for which you want to apply for an ICP Filing service number. Click **Apply** from the information window of the instance. If the button **Apply** is not displayed, it indicates that this server does not meet the requirement. See [Why are the buttons not displayed on my page?](#concept_z4d_drl_zdb/section_hk3_pmz_zdb).

    The following figure shows how to apply for an ICP Filing service code.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14195/5698_en-US.png)

3.  Click **OK**  to confirm your application for a service code.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14195/5699_en-US.png)

    Once your application is successfully completed, you can view the ICP service code on the ICP No. Management page.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14195/5700_en-US.png)


## FAQs {#section_okl_m3z_zdb .section}

## Why is the Apply button on my ICP No. Application page not displayed? {#section_hk3_pmz_zdb .section}

If the button **Apply** is not displayed, the reasons are:

-   The account you log on with is not the account you use when purchasing the ECS instance.
-   When purchasing the ECS instance, you select Pay-As-You-Go as the payment method, which is not supported by ICP Filing. To change the payment method, see  [Switch from Pay-As-You-Go to Subscription](https://help.aliyun.com/document_detail/49884.html?spm=a2c4g.11186623.2.8.ICh21p).
-   The payment method of your ECS instance is Subscription, but the remaining time of the subscription is shorter than 3 months which is required by Alibaba  Cloud ICP Filing rule.  If your remaining subscription time is not long enough, renew your subscription to meet the requirement. If you have not bought Internet bandwidth, you must buy it. See the instructions in [Upgrade/Downgrade Configurations](https://help.aliyun.com/document_detail/25437.html?spm=a2c4g.11186623.2.9.ICh21p) to buy Internet bandwidth.
-   Your ECS instance has been expired. You cannot apply for an ICP Filing service code for an expired server.
-   You have already reached the maximum limit of ICP Filing service code applications for this ECS instance. You can apply for at most five ICP Filing service codes for an ECS instance. In this case, you must buy a new ECS instance for filing a new website.
-   The region selected for the Alibaba Cloud ECS you purchased is not in mainland China. If your ECS instance is in regions outside mainland China, you are not required to file with the MIIT.

    **Note:** If the region of your ECS instance is Hongkong, you do not apply for an ICP Filing.


## Why is “No available IPs for this ECS instance” displayed? {#section_nk3_pmz_zdb .section}

Currently, an Alibaba Cloud ECS can be used for product verification in ICP Filing only if it has Internet bandwidth and Internet IP. To get the Internet IP, make sure you have Internet bandwidth for the instance. To get the Internet IP,  you must buy Internet bandwidth for the instance. See the instructions in [Upgrade/Downgrade Configurations](https://help.aliyun.com/document_detail/25437.html?spm=a2c4g.11186623.2.15.ICh21p) to buy Internet bandwidth.

## I have not purchased an Alibaba Cloud ECS instance. Can I get an ICP Filing service code? {#section_ok3_pmz_zdb .section}

No. If you want to apply for an ICP Filing service code, you must buy an Alibaba Cloud ECS instance first.

