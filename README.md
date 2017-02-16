# MDB-3-DataTable-Style
 
[DataTables](https://datatables.net/) comes with few themes, including those for Bootstrap 3 and 4. These themes work really well for [Material Design for Bootstrap](https://mdbootstrap.com/mdb3/) (MDB) as is, but... 

This work enhances the Bootstrap 3 theme and takes advantage of the nice pagination and inputs available in MDB to make it look even even better!

Initially only the [pagination](https://mdbootstrap.com/mdb3/components/pagination/) was implemented but, with some help and advice from Allan I got the filter input as well as the length select to work, using [Input Fields](https://mdbootstrap.com/mdb3/components/forms/#section1) and [Material Select](https://mdbootstrap.com/mdb3/components/forms/#select-material) respectively.
  
There is presently no support for [custom renderers](https://datatables.net/reference/option/renderer) for these elements so the `"initComplete"` function has been hijacked. Once custom renderers are implemented I'll move the work over to a that mechanism.

Once I have more time I'll also adapt it so that it will work with BootStrap 4 and [MDB4](https://mdbootstrap.com/).