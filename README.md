repo init -u https://github.com/LineageOS/android.git -b lineage-19.1

source build/envsetup.sh

lunch  lineage_satsuki-eng

croot

brunch  satsuki
