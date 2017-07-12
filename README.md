# Espresso
Build samples of the Perfecto instrumented test gradle plugin.

In the samples folder you can view 4 ways of how to run the Perfecto plugin:
	<ul>
	<li>defaultAndroidProjectSample - an Android project with the plugin Json config file located in the default place</li>
	<li>localJarSample - an Android project configured to run with the Perfecto plugin jar file locally</li>
	<li>pluginConfigurationSample - an Android project with the cloudURL/security token configured in the build.gradle file</li>
	<li>remoteRunSample - how to run the plugin without the source code and only with apk's</li>
	</ul>

In the configFilesSamples folder you can see different examples of how it's possible to configure the plugin.
Except for devices, all parameters can be overriden by the command line.
