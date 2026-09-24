# Privacy Policy

This privacy policy applies to the Ulysses app for Android (the "Application"), operated by Caspar Münzinger (the "Service Provider"). It describes what information the Application processes, where that processing takes place, and what rights you have.

Effective date: 24 September 2026

## 1. Summary

The Application processes information only on your device. It has no Internet permission, so the Android operating system prevents it from establishing any network connection. The Service Provider operates no server, no user accounts, no analytics, no advertising and no crash reporting in connection with the Application. No information that the Application processes is transmitted to the Service Provider or to any third party.

## 2. Controller and contact

Caspar Münzinger
Email: contact@muenzingersystems.com

## 3. Purpose of the Application

The Application is a self-binding tool against unwanted consumption of sexually explicit content. The user makes a "pact" with chosen settings. While the pact is active, the Application detects sexually explicit images shown on the screen of the device and interrupts their display. Detection is performed by an image-classification model that is bundled with the Application and executed locally.

## 4. Use of the Android Accessibility Service

The Application uses the Android Accessibility Service as its detection mechanism. Through this service the Application:

- determines which application is in the foreground,
- reads the text visible on the screen in order to decide whether a screenshot is required, and
- takes screenshots of the screen through the system function provided by the service.

Each screenshot is reduced in size, evaluated by the local model in the working memory of the device and discarded immediately afterwards. Screenshots are not saved, not displayed to the Service Provider and not transmitted anywhere.

The service is activated only after you have read and accepted the disclosure shown in the Application and have enabled the service yourself in the Android system settings. You may disable the service at any time in the same settings. The Application does not interfere with system settings and does not prevent its own uninstallation.

The Accessibility Service is not used for any purpose other than the detection described above.

## 5. Information stored on the device

The following information is stored in the private storage area of the Application on your device:

- **Pact settings:** whether a pact is active, the selected sensitivity, the selected waiting period for loosening the pact, the time at which the pact was made, and any pending changes to these settings together with their timestamps.
- **Interruption records:** for each interruption, a timestamp and the detection score. No image and no screen content is stored.
- **Technical metrics:** a local log of detector performance (for example processing time per frame and number of interruptions) without any screen content.
- **Application preferences:** local configuration values.

This information is not transmitted. Android backup is disabled for the Application, so the information is not included in device backups.

## 6. Other permissions

- **Display over other apps:** used to show the interruption screen over the detected content.
- **Foreground service and start after boot:** used so that chosen waiting periods continue to run and a persistent status notification can be displayed.
- **Notifications:** used to display the status notification.
- **Close background processes:** used when you choose to return to the home screen after an interruption.

None of these permissions is used to collect or transmit information.

## 7. Legal basis

To the extent that the processing described above concerns personal data, it is carried out on the basis of Article 6(1)(b) of the General Data Protection Regulation (GDPR), namely to provide the function you have requested, and Article 6(1)(a) GDPR with respect to the analysis of screen content, for which you give consent in the Application and in the Android system settings. You may withdraw this consent at any time by disabling the Accessibility Service.

## 8. Retention and deletion

Screenshots are not retained. All other information described in section 5 remains on the device until you delete it. You can delete it at any time by clearing the Application's data in the Android system settings or by uninstalling the Application.

## 9. Third parties

The Application does not share information with third parties. It contains no third-party software development kits that collect or transmit information. The detection model is included in the Application and runs locally.

## 10. Children

The Application is intended for adults. It is not directed at, and must not be used by, persons under 18 years of age.

## 11. Your rights

Under the GDPR you have the rights of access, rectification, erasure, restriction of processing, data portability and objection, and the right to lodge a complaint with a supervisory authority. Because the Application transmits no information to the Service Provider, the Service Provider does not hold personal data about you and cannot access the information stored on your device. You can exercise your rights directly on the device as described in section 8. For questions about this policy, contact the Service Provider at the address given in section 2.

## 12. Changes to this policy

The Service Provider may update this policy when the Application changes. The current version is published at https://cmuenzin.github.io/ulysses-privacy/ together with its effective date.
