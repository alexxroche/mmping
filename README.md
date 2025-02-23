# mmping
  (Linux) Multi Metric Ping; ping from multiple interfaces

  mmping uses `iproute2` to alter the route metrics, sending
a ping between each rotation.

  This means that if a computer has both an ethernet and wifi
connection, then you can compare the ping times to the default
router.

  The default destination is the current default router, but
any IPv4 address is currently valid.

TODO: finish IPv6 support before all of the ISPs manage to.
