# Energy Tracking App

App to track your energy, water, gas or whatever consumptions.

## Import / Export

### Data

data could be exported in `CSV` format. Each line consists of a `date` in format __`YEAR-MONTH-DAY`__ OR __`YEAR-MONTH-DAY HH:MM`__ and a `value`, separated by `TAB`

```
2011-01-25   6556.0
2011-01-28   6700.2
```

or

```
2011-01-25 13:40   6556.0
2011-01-28 14:21   6700.2
```

to import use the same format.


### Backup

You can backup your meters with all data, and later import it. The data in backup is saved in `JSON` format and contains both, meter details and all data.

```
{
  "meter":{
    "title": "Water-Meter 1",
    "meterId": "D12234-01",
    "units": "m3"
  },
  "values":[
    {
      "date": "2019-01-11",
      "value": 1334
    },
    {
      "date": "2019-02-10",
      "value": 1500
    }
  ]
}
```

### Autosync

You can activate `Autosync` functionality in the "Edit Meter" view. Autosync is perfomed each time you add/remove data. Autosync-files using `JSON` format same as for backups.

> autosync is PREMIUM feature


### Google Drive

The app has integration with Google Drive to import/export data, backup or autync data.

> This is PREMIUM feature

# Privacy Policy

Quadriq Apps built the Energy Tracker app as a Free app. This SERVICE is provided by Quadriq Apps at no cost and is intended for use as is.

This page is used to inform visitors regarding my policies with the collection, use, and disclosure of Personal Information if anyone decided to use my Service.

If you choose to use my Service, then you agree to the collection and use of information in relation to this policy. The Personal Information that I collect is used for providing and improving the Service. I will not use or share your information with anyone except as described in this Privacy Policy.

The terms used in this Privacy Policy have the same meanings as in our Terms and Conditions, which is accessible at Energy Tracker unless otherwise defined in this Privacy Policy.

**Information Collection and Use**

For a better experience, while using our Service, I may require you to provide us with certain personally identifiable information. The information that I request will be retained on your device and is not collected by me in any way.

The app does use third party services that may collect information used to identify you.

Link to privacy policy of third party service providers used by the app

*   [Google Play Services](https://www.google.com/policies/privacy/)
*   [AdMob](https://support.google.com/admob/answer/6128543?hl=en)

**Log Data**

I want to inform you that whenever you use my Service, in a case of an error in the app I collect data and information (through third party products) on your phone called Log Data. This Log Data may include information such as your device Internet Protocol (“IP”) address, device name, operating system version, the configuration of the app when utilizing my Service, the time and date of your use of the Service, and other statistics.

**Cookies**

Cookies are files with a small amount of data that are commonly used as anonymous unique identifiers. These are sent to your browser from the websites that you visit and are stored on your device's internal memory.

This Service does not use these “cookies” explicitly. However, the app may use third party code and libraries that use “cookies” to collect information and improve their services. You have the option to either accept or refuse these cookies and know when a cookie is being sent to your device. If you choose to refuse our cookies, you may not be able to use some portions of this Service.

**Service Providers**

I may employ third-party companies and individuals due to the following reasons:

*   To facilitate our Service;
*   To provide the Service on our behalf;
*   To perform Service-related services; or
*   To assist us in analyzing how our Service is used.

I want to inform users of this Service that these third parties have access to your Personal Information. The reason is to perform the tasks assigned to them on our behalf. However, they are obligated not to disclose or use the information for any other purpose.

**Security**

I value your trust in providing us your Personal Information, thus we are striving to use commercially acceptable means of protecting it. But remember that no method of transmission over the internet, or method of electronic storage is 100% secure and reliable, and I cannot guarantee its absolute security.

**Links to Other Sites**

This Service may contain links to other sites. If you click on a third-party link, you will be directed to that site. Note that these external sites are not operated by me. Therefore, I strongly advise you to review the Privacy Policy of these websites. I have no control over and assume no responsibility for the content, privacy policies, or practices of any third-party sites or services.

**Children’s Privacy**

These Services do not address anyone under the age of 13\. I do not knowingly collect personally identifiable information from children under 13\. In the case I discover that a child under 13 has provided me with personal information, I immediately delete this from our servers. If you are a parent or guardian and you are aware that your child has provided us with personal information, please contact me so that I will be able to do necessary actions.

**Changes to This Privacy Policy**

I may update our Privacy Policy from time to time. Thus, you are advised to review this page periodically for any changes. I will notify you of any changes by posting the new Privacy Policy on this page. These changes are effective immediately after they are posted on this page.

**Contact Us**

If you have any questions or suggestions about my Privacy Policy, do not hesitate to contact me.

This privacy policy page was created at [privacypolicytemplate.net](https://privacypolicytemplate.net) and modified/generated by [App Privacy Policy Generator](https://app-privacy-policy-generator.firebaseapp.com/)
