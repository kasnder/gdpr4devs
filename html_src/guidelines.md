**This is no legal advice, but only an app developer's endeavour to make data protection more approachable.**
{: style="color:gray; font-size: 80%; text-align: center;"}

If you have app users from the European Union, you are responsible for
all personal data collected through your app. Personal data means all
data that relates to individuals. This may even include user identifiers
and IP addresses. Also “anonymous” data or device data can qualify as
personal data, if it can be related to individuals, and you must protect
it. You are responsible for any personal data collected on behalf of
third-parties, such as advertising, analytics, or crash reporting
services.

**Risk evaluation and record keeping.**
GDPR acknowledges that there
will never be full protection of personal data. Instead, it encourages a
risk-based approach, that is, seriously analysing the possible risks to
data protection. If you can prove that you took all reasonable measures,
there is no need to be overly afraid of high penalties. Make sure that
you can provide such proof, by *keeping records of all data protection
considerations and actions*.

**Handling user requests.**
The GDPR entitles users to manage (e.g.
access, delete, correct) any data about them. You can implement these
user rights directly in software, which would show your efforts towards
GDPR compliance. Yet, taking requests via email seriously is just as
fine. You have one month to respond to user requests.

**Reasonable data collection.**
-   You and your third-parties may only collect personal data
    reasonably, that is, restricted to what is necessary for service
    provision.
-   *iOS:* Always ask for user consent, before you or your third-parties
    collect *any data*, even if not related to the user.<br>
    *Android:* If you process sensitive data (e.g. health-related), or
    process data in unexpected ways, do tell the user in a clear manner
    and ask for his *consent* (no pre-ticked boxes allowed).
-   At best, use at most one third-party service for one purpose, that
    is, at most one advertising, analytics, and crash reporting service.
-   Check with every app release, if you can remove any third-party
    services.
-   Verify the default settings of your third-party services (on-device
    and server-wise), since third-parties have an interest in collecting
    ever more data. Only activate third-party services, once user
    consent is established.
-   If your app is aimed at *children*, do not employ any third-party
    services.

**Always provide a privacy policy.** Provide a privacy policy on the app
store and within the app. You may want to use one of the privacy policy
generators, such as [iubenda.com](iubenda.com). Make sure it discloses
the data collection of you and your third-parties adequately.

**Security measures and data breaches.** Take the standard measures for
security, such as HTTPS communications, salted passwords, validation of
user inputs. Apple[^1] and Google[^3] provide comprehensive guidance
on this. Try to remove identifiable information whenever possible,
through pseudonymisation or anonymisation. If you experience a *personal
data breach*, you must notify the data protection authority[^4]
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
Data Protection Authority, called ICO, provides excellent guidance[^5]
on data protection.

[^1]: <https://developer.apple.com/documentation/security> <https://developer.apple.com/library/archive/documentation/Security/Conceptual/SecureCodingGuide>

[^3]: <https://developer.android.com/training/articles/security-tips>

[^4]: <https://edpb.europa.eu/about-edpb/board/members>

[^5]: <https://ico.org.uk/for-organisations/>