---
group:
  - technology
---
AWS Device Farm is a testing service that allows you to test your web and mobile applications across a wide range of real physical phones and tablets hosted by AWS, without having to provision and manage testing infrastructure. The service enables you to improve the quality of your applications by testing against real devices with different hardware, operating systems, and configurations.

## Key Features

- **Real device testing**: Test on actual physical devices (not emulators or simulators).
- **Extensive device pool**: Access to a large variety of smartphones and tablets.
- **Automated testing**: Run automated tests on multiple devices in parallel.
- **Manual testing**: Interact with devices through remote access.
- **Screenshot capture**: Automatically capture screenshots during test runs.
- **Video recording**: Record videos of test sessions.
- **Performance data**: Collect CPU, memory, and other performance metrics.
- **Log collection**: Gather detailed logs for debugging.
- **Custom test environments**: Upload your own test frameworks and scripts.
- **Built-in test frameworks**: Leverage pre-configured test suites.
- **Device state management**: Reset to a clean state between tests.
- **Private device fleets**: Set up and manage your own private devices.
- **BYOD option**: Test on your own physical devices hosted in AWS.
- **Continuous integration**: Integrate with CI/CD systems.
- **Slot-based testing**: Run tests on multiple devices simultaneously.

## Supported Platforms

- **Android**: Test native and hybrid Android applications.
- **iOS**: Test native and hybrid iOS applications.
- **Web applications**: Test responsive web applications.
- **Xamarin**: Test Xamarin-based cross-platform applications.
- **Unity**: Test Unity-based games and applications.
- **React Native**: Test React Native applications.
- **Ionic**: Test Ionic framework applications.
- **Flutter**: Test Flutter-based cross-platform applications.
- **Cordova/PhoneGap**: Test Cordova-based applications.

## Testing Types

- **Automated testing**: Running scripted tests without human intervention.
    
    - **Built-in tests**: No-code testing with pre-built test suites.
    - **Custom tests**: Upload and run your own test scripts and frameworks.
    - **Standard test suites**: Use industry-standard testing frameworks.
    - **XCTest**: For iOS applications.
    - **Espresso**: For Android applications.
    - **Appium**: Cross-platform test framework.
    - **Calabash**: Cross-platform test framework.
    - **UI Automator**: For Android UI testing.
    - **JUnit**: For Java-based testing.
    - **Robot Framework**: Generic test automation framework.
- **Remote access testing**: Manual interaction with devices.
    
    - **Interactive testing**: Real-time interaction with devices.
    - **Exploratory testing**: Ad-hoc testing to discover issues.
    - **Usability testing**: Test user experience directly.
    - **Debugging**: Identify and diagnose issues in real-time.
    - **Live screen sharing**: Share device screens with team members.
    - **Remote device control**: Control devices remotely through the browser.

## Common Use Cases

- **Cross-device compatibility testing**: Verify app works across different devices.
- **Regression testing**: Ensure new code doesn't break existing functionality.
- **Performance testing**: Measure app performance across various devices.
- **User experience testing**: Evaluate app usability on different screen sizes.
- **Continuous integration**: Automatically test new builds as part of CI/CD pipeline.
- **OS version compatibility**: Test on multiple OS versions.
- **Network condition testing**: Test performance under different network conditions.
- **Location-based testing**: Test features that depend on geographical location.
- **Pre-release validation**: Final verification before releasing to app stores.
- **In-app purchase testing**: Verify payment flows work correctly.
- **Push notification testing**: Test push notification delivery and handling.
- **Device-specific bug reproduction**: Reproduce and fix bugs on specific devices.
- **Internationalization testing**: Test language and regional adaptations.
- **Battery consumption testing**: Measure app impact on device battery.

## Integration with AWS Services

- **[[AWS CodePipeline]]**: Integrate device testing into CI/CD pipelines.
- **[[AWS CodeBuild]]**: Build applications for testing.
- **[[AWS Lambda]]**: Create custom test workflows and automation.
- **[[Amazon S3]]**: Store test artifacts, screenshots, and videos.
- **[[Amazon CloudWatch]]**: Monitor test executions and results.
- **[[AWS Identity and Access Management (IAM)]]**: Control access to Device Farm resources.
- **[[Amazon Simple Notification Service (Amazon SNS)]]**: Receive notifications about test results.
- **[[AWS CloudTrail]]**: Audit Device Farm API usage.

## Benefits

- **Reduced hardware costs**: No need to purchase and maintain device inventory.
- **Expanded device coverage**: Test on more devices than would be practical to own.
- **Latest devices**: Access to current device models and OS versions.
- **Parallel testing**: Run tests on multiple devices simultaneously.
- **Faster release cycles**: Accelerate testing without hardware constraints.
- **Improved app quality**: Catch device-specific issues before users do.
- **Detailed reporting**: Comprehensive test reports with multimedia artifacts.
- **Consistent test environment**: Reliable, clean testing environment for each test.
- **Geographic flexibility**: Test from anywhere with internet access.
- **Pay-as-you-go pricing**: Pay only for the testing time you use.
- **Reduced time-to-market**: Faster testing means quicker releases.
- **Simplified testing process**: Streamlined testing workflow.

## Pricing

AWS Device Farm pricing is based on:

- **Device minutes**: Pay for the time your tests run on devices.
- **Device slots**: For unmetered remote access testing.
- **Private device setup**: Additional charges for private device fleets.

Pricing varies by testing method:

- **Automated testing**: Pay per device minute with bulk discounts available.
- **Remote access (manual) testing**: Pay for device slots with unlimited testing time.
- **Private devices**: Additional charges for hosting your own devices.

A free tier is available for new users, including a limited number of device minutes.