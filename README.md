# OpenWRT custom binary packages

Run the following command to add opkg custom feed:

    (. /etc/openwrt_release; echo "src/gz openwrt_azuwis http://azuwis.github.io/openwrt-binary-packages/${DISTRIB_ARCH}/azuwis" >> /etc/opkg/customfeeds.conf)
