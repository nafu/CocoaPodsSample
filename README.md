##CocoaPods Best Practices

1. use the same version of CocoaPods
2. specify the version of a pod
3. specify the version of your Ruby

###1.use the same version of CocoaPods

In Gemfile

	source 'https://rubygems.org'

	gem 'cocoapods', '0.17.2'

###2.specify the version of a pod

In Podfile

	platform :ios
	pod 'JSONKit',        '~> 1.4'
	target :CocoaPodsSampleTests, :exclusive => true do
  		pod 'Kiwi',         '~> 2.0.6'
	end

###3.specify the version of your Ruby

In .ruby-version

	1.9.3-p327

##Links

[CocoaPods](http://cocoapods.org)

[rbenv](https://github.com/sstephenson/rbenv)

[CocoaPods Best Practices](http://9elements.com/io/index.php/cocoapods-best-practices/)

