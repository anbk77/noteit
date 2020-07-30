# Note It

A simple note taking app using Rails and twitter bootstrap. Db used is mariaDB 10.1

## Setup

Ruby version : `1.8.7p-374`

Rails : `2.3.5`

delayed_job 2.0.4 as plugin: `script/plugin install git://github.com/collectiveidea/delayed_job.git -r v2.0`
 
`script/generate delayed_job`

`rake db:create`

`rake db:migrate`

Start delayed_job: `script/delayed_job start`


## Assignment tasks

Use twitter bootstrap for the UI and make the layout responsive while accessing with mobile phones.

New users can Sign Up for the app (registration)

Validate username (existing or available)

Send confirmation email (use delayed_job  '2.0.4' for queuing)

Existing users can login

Forgot password

Create Notes (Use an editor like http://imperavi.com/redactor/)

Edit notes

Delete notes

Advanced - Create public notes with url which can be read by anyone with the url
