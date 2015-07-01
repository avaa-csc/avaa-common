To get liferay_portlet_parent_pom.xml working, make sure to set LIFERAY_HOME environment variable to point to your liferay installation.

To use the pom files in this directory in any project, please use Maven profile "liferay". E.g., if you package and deploy a project to liferay, use command "mvn clean package liferay:deploy -Pliferay" when in the project's pom folder.