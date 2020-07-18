# Adding a Cloud Archive Location

**Using Azure blob storage as an example, let’s walk through adding an archive location:**

Click on the gear icon located on the top right bar of the web UI.

The Settings menu appears.

![](../../.gitbook/assets/screen-shot-2020-07-18-at-11.52.11.png)

From the **Settings** menu, select **Archival Locations**.

The Archival Locations page appears.

Click the blue **+** icon.

![](https://lh6.googleusercontent.com/LVrv2jjcLhIB5kZ54eQFWECbWn3Rdo5u9mVSWHgbIOW4Ls1j0Ze1NztRtPQ9-i9KczbJosyw2MWT8pvlfHYI20Amks1jbfe9LSuYhjXG_Xp-JGakLHyiVZMoOh3hJk_CmNmbWx9d)

The Add Archival Location dialog box appears.

In Archival Type, select **Azure**.

 The Microsoft Azure archival location fields appear.

![](https://lh6.googleusercontent.com/DHdw2uPQ9eN1OtQgetEipZLpmuBcxHU7dcFdmPFD3Otd6o6rZpDN9X57KDuu4asQ0EkqsHotT_o4cDwDt_riv3fYuoDeee6NbZ1msE7eofOc9iqJevFcG4qGkJPSm_8ysRanzduD)

Review the different inputs required for **Microsoft Azure** as an archive. Feel free to browse other archive types to view required settings.

Press **Cancel** when finished.

On the left pane of the web UI, select **SLA Domains** > **Local Domains**. The Local SLA Domains page appears.

Select the Camp Rubrik SLA Domain that you previously created. The SLA Domain page will load.

Click the ellipses (`...`) at the top right corner of the SLA Domain page. Select **Edit**.

Click **Configure Remote Settings** at the bottom of the dialog (depending on the resolution of your screen it may be necessary to scroll down).

In Archival, click the toggle (if not already done). Notice the **Enable Instant Archive** option. Do not select it at this time although you can click the circled “`i`” to read what it does.

![](https://lh5.googleusercontent.com/5cNsnDgGkE20DeySY-B7DA389b9CTQEBgJSAHrUShLgAiFmCIu5hGE4wWXAOCcDO9_cFx9dKMXaNAWF4wWau7hEXjUcPlAaxuinMvMIasqXTTXS8SY1YhEyy0ycxFHaLR9-Wzquc)

The Instant Archive feature can be enabled to instruct a Rubrik cluster to immediately queue a task to copy a new snapshot to a specified archival location.

Press **Cancel**.