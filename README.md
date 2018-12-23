config.json for v2ray need v2ctl;
config.pb for v2ray no need v2ctl;
run v2ctl config < config.json > config.pb on local linux to get config.pb;
manifest.yml for go_buildpack on cloud foundary,and use cf push -b https://github.com/cloudfoundry/go-buildpack.git to use the last go_buildpack;
