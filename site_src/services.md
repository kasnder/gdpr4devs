Implementation guidance for the most commonly used third-party services, as well as links to their GDPR guidelines.

**Adjust**.
Once the Adjust SDK is enabled in your app, data sharing takes place,
notably of device events. User consent should be established before
enabling this SDK. It stands out that Adjust integrates the GDPR *right
to deletion* into their SDK. This could be implemented in your app, to
show your efforts to comply with GDPR.

*More info:*
<https://github.com/adjust/sdks>{:target="_blank"}

**AppLovin**.
For EU users, AppLovin requires consent to be passed on
programmatically. If consent is given, the Advertising ID and IP address
will be sent to advertising partners, otherwise only a country code.
Once loaded at runtime, AppLovin automatically receives the information
that the app was installed.


*More info:*
<https://www.applovin.com/gdprfaqs/>{:target="_blank"}

**AppsFlyer**.
The service collects the Advertising ID and a unique AppsFlyer user ID
from the first app start. User consent should be established before
activating this service. If the Advertising ID cannot be accessed,
permanent identifiers, notably the device’s IMEI, are shared with
AppsFlyer, unless programmatically disabled. Such permanent identifiers
are highly critical from a data protection standpoint. This practice
should be communicated transparently to the user, if not disabled.

*More info:*
<https://support.appsflyer.com/hc/en-us/articles/360001422989>{:target="_blank"}

**Facebook SDK**.
From the first app start, the Facebook SDK collects device information
and events (app installation, app start, in-app purchases), unless
programmatically disabled. User consent should be established before
activating this SDK. Facebook serves no advertising, if the user limits
interest-based ads from the device settings.

*More info:*
<https://developers.facebook.com/docs/app-events/best-practices/gdpr-compliance>{:target="_blank"}

**Flurry**.
For ads, this service provides a complicated mechanism to establish a
user consent. Since legally required for many advertising services, you
may want to consider easier, alternative approaches to establish valid
user consent. Unless programmatically disabled, the user location is
collected for analytics purposes, if the app has the permission to
retrieve such. This is highly invasive and may violate GDPR. At very
least, this practice should be disclosed to the user transparently, if
not disabled. Generally, user consent should be established before
activating this service.

*More info (Analytics):*
<https://developer.yahoo.com/flurry/docs/analytics/gdpr/summary>{:target="_blank"}

*More
info (Ads):* <https://developer.yahoo.com/flurry/docs/publisher/gdpr/>{:target="_blank"}

**Google AdMob**.
This service serves personalised advertising by default, violating
Google’s policies if used in the EU. This must be changed by the
developer, such that user consent is established prior to serving
personalised ads. AdMob shares device statistics and events with Google
from the first app start, unless programmatically changed. User consent
should be established before activating this service.

*More info:*
<https://developers.google.com/admob/android/eu-consent#forward_consent_to_the_google_mobile_ads_sdk>{:target="_blank"}

**Google Analytics**.
User opt-out and IP anonymisation are supported programmatically and
their implementation should be considered. User consent should be
established before using this service.

*More info:*
<https://developers.google.com/analytics/devguides/collection/android/v4/advanced>{:target="_blank"}

**Google Chrashlytics**.
This service shares crash reports with Google from the first app start,
unless changed by the developer. User consent should be established
before activating this service.

*More info:*
<https://firebase.google.com/docs/crashlytics/customize-crash-reports#enable_opt-in_reporting>{:target="_blank"}

**Google DoubleClick**.
This service serves personalised advertising by default, violating
Google’s policies if used in the EU. User consent should be established
before activating this service.

*More info:*
<https://developers.google.com/ad-manager/mobile-ads-sdk/android/eu-consent#forward_consent_to_the_google_mobile_ads_sdk>{:target="_blank"}

**Google Firebase Analytics**.
This service collects device statistics from the first app start, unless
changed by the developer. The collected data includes the Google
Advertising ID, unless programmatically disabled, and may be used for
advertising purposes under certain circumstances. User consent should be
established before activating this service.

*More info:*
<https://firebase.google.com/docs/analytics/configure-data-collection>{:target="_blank"}

**Inmobi**.
The Inmobi SDK only collects personal data, if you explicitly indicate
to the SDK that user consent was established. If no consent is given,
unpersonalised ads are shown to the user. Inmobi encourages you to
provide data about location and demographics for higher revenue, if you
programmatically pass on this information. Such sensitive data
collection should be transparently disclosed to the user, if not
refrained from.

*More info:*
<https://support.inmobi.com/monetize/faqs/gdpr-guide-for-publishers/>{:target="_blank"}

**MoPub**.
For increased advertising revenue, MoPub shares data with two other
services, IAS and Moat, unless programmatically disabled. These services
must be transparently communicated to the user, if not disabled. User
consent should be established before activating this service.

*More info:*
<https://developers.mopub.com/publishers/best-practices/gdpr-guide/>{:target="_blank"}

**Unity Ads**.
Unity automatically asks for user consent, unless a special arrangement
is reached with Unity. Personal data is only collected if the user
consents. When ads are served, Unity provides the user with a “privacy
icon”, to change his opt-out setting. If the user opts-out, all
collected data is deleted.

*More info:*
<https://unity3d.com/de/legal/gdpr>{:target="_blank"}