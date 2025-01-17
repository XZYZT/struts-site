---
layout: default
title: Announcements 2023
---

# Announcements 2023
{:.no_toc}

* Will be replaced with the ToC, excluding a header
{:toc}

<p class="pull-right">
  Skip to: <a href="announce-2022">Announcements - 2022</a>
</p>

#### 13 September 2023 - Apache Struts version 6.3.0.1 General Availability {#a20230913-1}

The Apache Struts group is pleased to announce that Apache Struts version 6.3.0.1 is available as a "General Availability"
release. The GA designation is our highest quality grade.

The Apache Struts is an elegant, extensible framework for creating enterprise-ready Java web applications.
The framework has been designed to streamline the full development cycle, from building, to deploying,
to maintaining applications over time.

This version addresses a potential **security vulnerability** described in [S2-065](https://cwiki.apache.org/confluence/display/WW/S2-065) - please read the mentioned security bulletins for more details.
This is a drop-in replacement and upgrade should be straightforward.

> Please read the [Version Notes]({{ site.wiki_url }}/Version+Notes+6.3.0.1) to find more details about performed
> bug fixes and improvements. 

**All developers are strongly advised to perform this upgrade.**

The 6.x series of the Apache Struts framework has a minimum requirement of the following specification versions:
Servlet API 3.1, JSP API 2.1, and Java 8.

Should any issues arise with your use of any version of the Struts framework, please post your comments to the user list,
and, if appropriate, file [a tracking ticket]({{ site.jira_url }}).

You can download this version from our [download](download.cgi#struts-ga) page.

#### 13 September 2023 - Apache Struts version 6.1.2.2 General Availability {#a20230913-2}

The Apache Struts group is pleased to announce that Apache Struts version 6.1.2.2 is available as a "General Availability"
release. The GA designation is our highest quality grade.

The Apache Struts is an elegant, extensible framework for creating enterprise-ready Java web applications.
The framework has been designed to streamline the full development cycle, from building, to deploying,
to maintaining applications over time.

This version addresses a potential **security vulnerability** described in [S2-065](https://cwiki.apache.org/confluence/display/WW/S2-065) - please read the mentioned security bulletins for more details.
This is a drop-in replacement and upgrade should be straightforward.

> Please read the [Version Notes]({{ site.wiki_url }}/Version+Notes+6.1.2.2) to find more details about performed
> bug fixes and improvements. 

**All developers are strongly advised to perform this upgrade.**

The 6.x series of the Apache Struts framework has a minimum requirement of the following specification versions:
Servlet API 3.1, JSP API 2.1, and Java 8.

Should any issues arise with your use of any version of the Struts framework, please post your comments to the user list,
and, if appropriate, file [a tracking ticket]({{ site.jira_url }}).

You can download this version from our [download](download.cgi#struts-ga) page.

#### 13 September 2023 - Apache Struts version 2.5.32 General Availability {#a20230913-3}

The Apache Struts group is pleased to announce that Apache Struts version 2.5.32 is available as a "General Availability"
release. The GA designation is our highest quality grade.

The Apache Struts is an elegant, extensible framework for creating enterprise-ready Java web applications.
The framework has been designed to streamline the full development cycle, from building, to deploying,
to maintaining applications over time.

This version addresses a potential **security vulnerability** described in [S2-065](https://cwiki.apache.org/confluence/display/WW/S2-065) - please read the mentioned security bulletins for more details.
This is a drop-in replacement and upgrade should be straightforward.

> Please read the [Version Notes]({{ site.wiki_url }}/Version+Notes+2.5.32) to find more details about performed
> bug fixes and improvements. 

**All developers are strongly advised to perform this upgrade.**

The 6.x series of the Apache Struts framework has a minimum requirement of the following specification versions:
Servlet API 3.1, JSP API 2.1, and Java 8.

Should any issues arise with your use of any version of the Struts framework, please post your comments to the user list,
and, if appropriate, file [a tracking ticket]({{ site.jira_url }}).

You can download this version from our [download](download.cgi#struts-ga) page.

#### 04 September 2023 - Apache Struts version 6.3.0 General Availability {#a20230904}

The Apache Struts group is pleased to announce that Apache Struts version 6.3.0 is available as a "General Availability"
release. The GA designation is our highest quality grade.

The Apache Struts is an elegant, extensible framework for creating enterprise-ready Java web applications.
The framework has been designed to streamline the full development cycle, from building, to deploying,
to maintaining applications over time.

> Note: This version includes the whole code of retired The Apache Tiles, when you use the Struts Tiles plugin
> please to remove any external dependencies to the Apache Tiles as the whole code is already included in the plugin.
> See [WW-5233](https://issues.apache.org/jira/browse/WW-5233) for more details.

Below is a full list of all changes:

**Bug**

- WW-5330 - Issue when submitting a form with a textarea containing more than 4000 characters.
- WW-5331 - Access to request attributes via tags is broken

**Improvement**

- WW-5233 - Include Apache Tiles code base in the Tiles plugin
- WW-5321 - notify / document about new maxStringLength limitation
- WW-5327 - Stop using JavaBeans notation for setters in SecurityMemberAccess & MemberAccessValueStack
- WW-5332 - Validate excluded package name list for missing commas
- WW-5334 - Misc VelocityManager code cleanup
- WW-5336 - Merge OgnlTool class into StrutsUtil class
- WW-5337 - Improve performance of excluded classes and packages

**Dependency**

- WW-5315 - Upgrades ASM to version 9.5
- WW-5316 - Upgrades commons-io to version 2.13.0
- WW-5317 - Upgrades log4j-api to version 2.20.0
- WW-5318 - Upgrades slf4j-api to version 2.0.7
- WW-5320 - finish Reproducible Builds
- WW-5322 - Upgrade Jackson version to 2.15.2
- WW-5323 - Upgrade JasperReports to version 6.20.5
- WW-5325 - Upgrade commons-lang3 to version 2.13.0
- WW-5329 - Upgrade xstream to version 1.4.20

> Please read the [Version Notes]({{ site.wiki_url }}/Version+Notes+6.3.0) to find more details about performed
> bug fixes and improvements.

**All developers are strongly advised to perform this upgrade.**

The 6.x series of the Apache Struts framework has a minimum requirement of the following specification versions:
Servlet API 3.1, JSP API 2.1, and Java 8.

Should any issues arise with your use of any version of the Struts framework, please post your comments to the user list,
and, if appropriate, file [a tracking ticket]({{ site.jira_url }}).

You can download this version from our [download](download.cgi#struts-ga) page.

#### 10 July 2023 - Apache Struts version 6.2.0 General Availability {#a20230710}

The Apache Struts group is pleased to announce that Apache Struts version 6.2.0 is available as a "General Availability"
release. The GA designation is our highest quality grade.

The Apache Struts is an elegant, extensible framework for creating enterprise-ready Java web applications.
The framework has been designed to streamline the full development cycle, from building, to deploying,
to maintaining applications over time.

Below is a full list of all changes:

**Bug**

- WW-4434 - datetextfield.ftl is missing
- WW-5199 - StrutsPrepareFilter and StrutsExecuteFilter do not support forwarding to another action
- WW-5263 - CSP related interceptors have wrong short names
- WW-5270 - Forwarding from a Struts excluded URL to an Action not working
- WW-5271 - Select tag NOT working when using list="#{ ... }"
- WW-5272 - java.lang.UnsupportedOperationException in the Time component
- WW-5276 - Cleanup method of request is not called
- WW-5289 - Execute and Wait Interceptor prevents JVM shutdown
- WW-5295 - s:date ignores LocalTime
- WW-5296 - Wrong DTD version
- WW-5301 - Impossible to select alternate default VelocityManager bean
- WW-5302 - Autogenerated html ID bases on unevaluated value of the name/action/method attributes
- WW-5307 - Confusing documentation about ognl
- WW-5309 - NamedVariablePatternMatcher throws when pattern begins with a variable
- WW-5310 - s:url does not handle equal sign correctly
- WW-5311 - NamedVariablePatternMatcher throws an IllegalArgumentException when named variable is not the last part of the sequence
- WW-5312 - ExecuteAndWaitInterceptor inconsistent wait processing behaviour

**New Feature**

- WW-5275 - Allow to configure more flexible Content-Security-Policy

**Improvement**

- WW-4404 - Implement HttpInterceptor
- WW-5196 - Make RequestMap and ApplicationMap to use generics, also correct SessionMap to always be of type <String, Object>
- WW-5243 - Removes support for "struts.mapper.action.prefix.crossNamespaces"
- WW-5251 - Remove deprecated interfaces used with ServletConfigInterceptor
- WW-5253 - Remove deprecated methods from DefaultUrlHelper
- WW-5261 - Refactor TagUtils#getStack()
- WW-5262 - Extract excluded classes and beans out of struts-default.xml
- WW-5264 - Extract XSLT result into a dedicated plugin
- WW-5265 - Allow removal of a single/specific container provider
- WW-5266 - Add configuration option for a per-file max size for  multipart requests
- WW-5268 - Add configuration option to exempt classes from OGNL  package exclusions
- WW-5273 - Support fileupload using native Servlet API 3.1 logic
- WW-5280 - Cleanup NoParameters interfaces
- WW-5283 - Update Struts Archetypes
- WW-5285 - Upgrade commons-fileupload to ver 1.5 and add option to  limit number of accepted files
- WW-5288 - Make excluded package exemption logic more strict
- WW-5290 - Refactor ConfigurationManager
- WW-5292 - Allow overriding of Operations classes in two filter setup  and assorted clean up
- WW-5293 - Allow loading XML configuration from other than filesystem
- WW-5304 - Drop deprecated methods from ActionContext
- WW-5308 - Add minlength and maxlength to textarea on javatemplates plugin
- WW-5314 - Do not log warnings for bad user input from JakartaMultiPartRequest

**Task**

- WW-5278 - Clean up duplicated code across ActionValidatorManagers
- WW-5279 - Improve readability of XmlConfigurationProvider class
- WW-5284 - Further clean up ActionValidatorManager implementations
- WW-5298 - Clean up StrutsVelocityContext
- WW-5299 - Clean up ActionChainResult
- WW-5300 - Make Dispatcher methods overridable

**Dependency**

- WW-5269 - Upgrade Jackson to version 2.14.1
- WW-5274 - Mark Pell Multipart plugin as deprecated
- WW-5277 - Upgrade Freemarker to version 3.2.32

> Please read the [Version Notes]({{ site.wiki_url }}/Version+Notes+6.2.0) to find more details about performed
> bug fixes and improvements.

**All developers are strongly advised to perform this upgrade.**

The 6.x series of the Apache Struts framework has a minimum requirement of the following specification versions:
Servlet API 3.1, JSP API 2.1, and Java 8.

Should any issues arise with your use of any version of the Struts framework, please post your comments to the user list,
and, if appropriate, file [a tracking ticket]({{ site.jira_url }}).

You can download this version from our [download](download.cgi#struts-ga) page.

#### 13 June 2023 - Apache Struts version 6.1.2.1 General Availability {#a20230613-1}

The Apache Struts group is pleased to announce that Apache Struts version 6.1.2.1 is available as a "General Availability"
release. The GA designation is our highest quality grade.

The Apache Struts is an elegant, extensible framework for creating enterprise-ready Java web applications.
The framework has been designed to streamline the full development cycle, from building, to deploying,
to maintaining applications over time.

This version addresses two potential **security vulnerabilities** described in [S2-063](https://cwiki.apache.org/confluence/display/WW/S2-063) 
and [S2-064](https://cwiki.apache.org/confluence/display/WW/S2-064) - please read the mentioned security bulletins for more details. 
This is a drop-in replacement and upgrade should be straightforward.

> Please read the [Version Notes]({{ site.wiki_url }}/Version+Notes+6.1.2.1) to find more details about performed
> bug fixes and improvements. Also, a dedicated [migration guide]({{ site.wiki_url }}/Struts+2.5+to+6.0.0+migration)
> has been prepared.

**All developers are strongly advised to perform this upgrade.**

The 6.x series of the Apache Struts framework has a minimum requirement of the following specification versions:
Servlet API 3.1, JSP API 2.1, and Java 8.

Should any issues arise with your use of any version of the Struts framework, please post your comments to the user list,
and, if appropriate, file [a tracking ticket]({{ site.jira_url }}).

You can download this version from our [download](download.cgi#struts-ga) page.

#### 13 June 2023 - Apache Struts version 2.5.31 General Availability {#a20230613-2}

The Apache Struts group is pleased to announce that Apache Struts version 2.5.31 is available as a "General Availability"
release. The GA designation is our highest quality grade.

The Apache Struts is an elegant, extensible framework for creating enterprise-ready Java web applications.
The framework has been designed to streamline the full development cycle, from building, to deploying,
to maintaining applications over time.

This version addresses two potential **security vulnerabilities** described in [S2-063](https://cwiki.apache.org/confluence/display/WW/S2-063)
and [S2-064](https://cwiki.apache.org/confluence/display/WW/S2-064) - please read the mentioned security bulletins for more details.
This is a drop-in replacement and upgrade should be straightforward.

> Please read the [Version Notes]({{ site.wiki_url }}/Version+Notes+2.5.31) to find more details about performed
> bug fixes and improvements

**All developers are strongly advised to perform this upgrade.**

The 6.x series of the Apache Struts framework has a minimum requirement of the following specification versions:
Servlet API 3.1, JSP API 2.1, and Java 8.

Should any issues arise with your use of any version of the Struts framework, please post your comments to the user list,
and, if appropriate, file [a tracking ticket]({{ site.jira_url }}).

You can download this version from our [download](download.cgi#struts-ga) page.

#### 10 March 2023 - Apache Struts version 6.1.2 General Availability {#a20230310}

The Apache Struts group is pleased to announce that Apache Struts version 6.1.2 is available as a "General Availability"
release. The GA designation is our highest quality grade.

The Apache Struts is an elegant, extensible framework for creating enterprise-ready Java web applications.
The framework has been designed to streamline the full development cycle, from building, to deploying,
to maintaining applications over time.

Below is a full list of all changes:

**Improvement**

- WW-5285 - Upgrade commons-fileupload to ver 1.5 and add option to limit number of accepted files

> Please read the [Version Notes]({{ site.wiki_url }}/Version+Notes+6.1.2) to find more details about performed
> bug fixes and improvements. Also, a dedicated [migration guide]({{ site.wiki_url }}/Struts+2.5+to+6.0.0+migration) 
> has been prepared.

**All developers are strongly advised to perform this upgrade.**

The 6.x series of the Apache Struts framework has a minimum requirement of the following specification versions:
Servlet API 3.1, JSP API 2.1, and Java 8.

Should any issues arise with your use of any version of the Struts framework, please post your comments to the user list,
and, if appropriate, file [a tracking ticket]({{ site.jira_url }}).

You can download this version from our [download](download.cgi#struts-ga) page.

<p class="pull-right">
  Skip to: <a href="announce-2022">Announcements - 2022</a>
</p>

<p class="pull-left">
  <strong>Next:</strong>
  <a href="kickstart">Kickstart FAQ</a>
</p>
