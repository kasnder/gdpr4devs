If you have app users from the European Union, you are responsible for personal data collected through your app.
Personal data is
data relating to individuals.
This may include device data, pseudonyms, user identifiers, advertising identifiers, (dynamic) IP addresses, and postcodes, especially in combination with other data.
For these reasons, it is usually not possible to make personal data non-personal.

You are also responsible for personal data collected from your app for third-party services, such as advertising, analytics, or crash reporting services.

**Risk evaluation and documentation.**
GDPR acknowledges that there
will never be full protection of personal data. Instead, it encourages a
risk-based approach, that is, seriously analysing the possible risks to
data protection and taking appropriate data protection measures. If you can prove that you took all appropriate measures,
there is no need to be overly afraid of high fines.

Make sure that you can provide such proof, by *documenting all data protection
considerations, decisions, and actions*.

**Reasonable data collection.**
You and your third-parties may only collect personal data
reasonably, that is, only for the
purposes stated in your privacy policy (purpose limitation) and 
restricted to what is necessary for the stated purposes (data 
minimisation).

Furthermore:
-   *iOS:* According the Apple's
    terms, you should ask for user consent, before you or your third-parties
    collect *any data*, no matter if personal and non-personal.<br>
    *Android:* According to Google's terms, if you process sensitive data (e.g. health-related), or
    process data in unexpected ways, do tell the user in a clear manner
    and ask for his *consent* (no pre-ticked boxes allowed).
-   At best, use at most one third-party service for one purpose, that
    is, at most one advertising, analytics, and crash reporting service.
-   Check with every app release, if you can reduce data collection or remove any third-party
    services.
-   Verify the default settings of your third-party services (on-device
    and server-wise), since third-parties have an interest in collecting
    ever more data.
    Only activate third-party services, once user
    consent is established. More information can be found in the Appendix below.
-   If your app is aimed at *children*, do not employ any third-party
    services. It's not good practice, and a violation of Apple's terms.
-   If possible, use libraries that make their source code available. Otherwise, you have no means to verify the underlying data practices.

**Always provide a privacy policy.** Provide a privacy policy on the app
store and within the app. You may want to use one of the privacy policy
generators, such as [iubenda.com](iubenda.com){:target="_blank"}.
Make sure it discloses
the data collection of you and your third-parties adequately.

**Handling user requests.**
The GDPR entitles users to manage (e.g.
access, delete, correct) any data about them. You can implement these
user rights directly in software, which would show your efforts towards
GDPR compliance. Yet, taking requests via email seriously is just as
fine. You have one month to respond to user requests.
This response may either address the request, or, for complex user requests, request an extension for a further 2 months.

**Security measures and data breaches.** Take the standard measures for
security, such as HTTPS communications, salted passwords, validation of
user inputs. Apple ([here](https://developer.apple.com/documentation/security){:target="_blank"} and [here](https://developer.apple.com/library/archive/documentation/Security/Conceptual/SecureCodingGuide){:target="_blank"}) and [Google](https://developer.android.com/training/articles/security-tips){:target="_blank"} provide comprehensive guidance
on this. Try to remove identifiable information whenever possible,
through pseudonymisation or anonymisation. If you experience a *personal
data breach*, you must notify [the data protection authority](https://edpb.europa.eu/about-edpb/board/members)
within 72 hours, plus the individuals in case of high risk.

**Consent for third-party services.** If you use third-party services,
the user must be asked for consent in almost all circumstances. This
consent must be sought before the third-party service is activated and
begins to share data. Beyond consent,
the Appendix below provides more detail on
the correct implementation of the most widely used third-party services.

**Closing remarks.** By implementing these measures, you should come an
important step closer to compliance with GDPR. Additionally, you should
consult the guidelines of an EU data protection authority. The British
Data Protection Authority, called ICO, provides [excellent guidance](https://ico.org.uk/for-organisations/){:target="_blank"}
on data protection.

