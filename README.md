# ZKBootstrap

If you use the [ZK Framework](https://www.zkoss.org) together with [Bootstrap](https://getbootstrap.com), you will notice that zk's CSS styles conflict with Bootstrap's, causing certain components to appear with the ZK style and other components as the bootstrap style.

This CSS file aims to eliminate these conflicts, making ZK elements have the Bootstrap style.

- All ZK input components (textbox, intbox, doublebox) must receive the Bootstrap "form-control" class.
- In Boostrap 5, the ZK listbox component must receive the Boostrap "select-control" class. In Bootstrap 4, the listbox must receive the "form-control" class.
- The ZK CSS was removed on Windows so that it is transparent.
- Datebox do not need "form-control" class.

Important: use the ZK Icelue theme for the best experience.