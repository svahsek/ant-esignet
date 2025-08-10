# Register Yourself

* Now you can self generate your own UIN Credential using the [Collab environment](https://collab.mosip.net/).
  * Click on the **Get UIN** button located at the top-right corner of the page. This will open the [Self Registration Form](https://self-register.collab.mosip.net/), Alternatively, you can simply click on this [link](https://self-register.collab.mosip.net/) to self register. You need to duly fill the self registration form.
  * On successful registration the UIN is sent to you over the email you used for registration, For more details you follow the [Generating Demo Credentials Guide](https://docs.mosip.io/1.2.0/general/collab-getting-started-guide/generating-demo-credentials).

You will be able to explore eSignet’s capabilities and experience seamless authentication through various channels.

## Step-by-Step Process

To experience the various methods of login and authentication in the demo health services portal using eSignet, follow the detailed instructions below:

### Step 1: Access the health services portal

Navigate to the relying party’s demo [**Health Services** ](https://healthservices-mosipid.collab.mosip.net/)portal in the Collab environment, and click on `Sign In with eSignet`.

### Step 2: Explore the various authentication mechanisms

#### OTP Authentication

Once you receive your UIN/VID, you can navigate to the [**health portal**](https://healthservices-mosipid.collab.mosip.net/) and try authenticating using your UIN/VID and the default OTP, i.e. "111111" (six ones).

A detailed step-by-step guide on how to log in with OTP using eSignet is also available [here](../end-user-guide/health-portal/login-with-otp.md).

{% hint style="info" %}
**Note:** Please use 111111 as the OTP, for any OTP-based feature in the Collab environment.
{% endhint %}

#### Biometrics-based Authentication

**Mock biometrics setup**

* To enable biometrics-based login, ensure that your machine is running Windows.
* Make sure you have Java 11 or a higher version installed on your computer.
* Download the `collab-mock-mds-auth.zip` file from the link provided [here](https://drive.google.com/drive/folders/14q7E5pZtfj0eimF3JGzlVfU4eV-MRPCQ).
* Unzip the downloaded file to extract its content.
* Locate the `run_auth.bat` file within the extracted folder.
* Double-click on the `run_auth.bat` file to start the authentication MDS.

Experience the process of logging in using biometrics, by following the instructions provided [here](../end-user-guide/health-portal/login-with-biometrics.md).

{% hint style="info" %}
**Note**: Biometric-based login with Mock MDS is currently unavailable in the Collab environment. Stay tuned to the MOSIP [Community](https://community.mosip.io/) for updates!
{% endhint %}

#### Authentication using Wallet

For our testing, we have integrated with [MOSIP's digital wallet- Inji](https://docs.inji.io/inji-wallet/inji-mobile), which we can use as an authenticator.

To get your credentials onboarded on Inji and enable them for authentication, follow the below steps,

1. Install the Inji APK on your mobile device using [this guide to set up and use Inji](https://docs.mosip.io/inji/inji-mobile-wallet/sandbox-details/inji-setup-guide)
2. Download your credentials on Inji. For details on how to download the credential, click [here](https://docs.inji.io/inji-wallet/inji-mobile/sandbox-details/inji-setup-guide#step-by-step-process) (Refer to step 3 in the guide)
3. Ensure that you have activated your credentials for online login. This step is crucial for wallet-based authentication to work smoothly. For a comprehensive guide on how to activate the VC for online login, refer [here](https://docs.inji.io/inji-wallet/inji-mobile/functional-overview/end-user-guide#activating-a-vc)

Once you are done with the above steps, you can use the Inji wallet to log into the health portal. The detailed steps to log into the health portal using the Inji wallet are available [here](../end-user-guide/health-portal/login-with-qr-code.md).

### Additional Video Resource

* Watch this informative video [here](https://www.youtube.com/watch?v=ZfUPRv71s_0,) to gain insights into eSignet.
* Explore the [eSignet Online Authentication Demo](https://www.youtube.com/watch?v=uNKlmw9KRFg) video for a practical demonstration of the authentication process.
* Watch [Running eSignet Locally](https://youtu.be/nmIZl6Tmt68?si=odKFq3UUQrV1kb6H) - A quick comprehensive guide for local implementation for eSignet versions up to 1.4.2
* Click [here](https://docs.esignet.io/) for detailed information about eSignet.

> By adhering to these guidelines and making use of the available resources, you will be able to smoothly experience the different methods of login and authentication offered by eSignet. This will guarantee secure and efficient access to the services you require.

### Get in Touch

If you require any assistance or encounter any issues during the testing and integration process, kindly reach out to us through the support mechanism provided below.

* Navigate to [Community](https://community.mosip.io/).
* Provide a detailed description of the support you require or provide detailed information about the issue you have encountered, including steps to reproduce, error messages, logs, and any other relevant details.
