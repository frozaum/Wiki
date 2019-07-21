# Depanare

## **First of all**

Make sure you have the [extension](../installation/extension.md) **and** the [application](../installation/application.md) installed!  
You can also try different steps. You don't have to try these in the order we put them here.

## Discord won't show the presence

### Be sure Discord is running NOT as administrator

Really important. Discord RPC won't work if you run Discord as an administrator.

### Check if you have antivirus or firewall running on your computer

Sometimes **antiviruses** and **firewalls** are **blocking applications** that are creating/hosting servers or just connecting to the internet. We're using the **local server** to **receive** and **pass** data between our app and extension, so if you will **block** app's ability to pass data you probably **won't** be able to use **PreMi**D.

You can **Google** more about antivirus and firewall disabling if you want to **fix** your problem.

### Make sure you've installed the latest version of PreMiD

You can check that by right-clicking on **'Check for updates'** the PreMiD icon in your taskbar.  
Otherwise the app will let you know when a new update is available.  
And you do not have to worry about the extension because it updates itself automatically.

{% hint style="info" %}
Dev versions and self-injected versions won't update automatically
{% endhint %}

![Windows taskbar](../.gitbook/assets/checkforupdates.png)

### Make sure that you've enabled Discord Rich Presence in settings

![Discord Game Activity](../.gitbook/assets/gameactivity_edited.png)

### Reload the page

You can press **Strg+R**/**F5** or **CMD+R** on your keyboard too instead of searching for the refresh button.

### Restart your browser

**Alt+F4** does a good job too. \(You have to start your browser again obviously\)

### Disable your addons

Disable all your addons and see if it works again.  
If yes, try to enable your addons step-by-step and tell us which addon broke PreMiD.

### Restart PreMiD \(App\)

![Windows taskbar](../.gitbook/assets/exit.png)

You have to restart PreMiD afterthought.

### Reload/restart Discord

Press **Strg+R** or **CMD+R** on you keyboard or restart Discord manually.

### Restarting your computer

I hope you know how to restart a computer.

### Reinstalling PreMiD

Sometimes there's something wrong with the files... Tutorials for installation can be found [here](../installation/application.md).

### Manual removal

{% tabs %}
{% tab title="Windows" %}
1. 1. Go to `C:\Users\USER\AppData\Local` and delete the folder `premid`
2. 1. Go to `C:\Users\USER\AppData\Roaming` and delete the folder`PreMiD`
{% endtab %}

{% tab title="Mac OS" %}
Go to `YOURDISK:/users/USER/~Library/Application Support` and delete the folder `PreMiD`
{% endtab %}
{% endtabs %}

Ping a staff member on our [Discord server](https://discord.gg/WvfVZ8T) if none of these steps helped.

## That hasn't solved my problem

You can either:

* [Open a issue](https://github.com/PreMiD/PreMiD/issues/new/choose) on [GitHub](https://github.com/PreMiD/PreMiD)
* Ask a staff member in [\#support](https://discord.gg/WvfVZ8T)

  


