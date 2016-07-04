source "https://supermarket.chef.io"

cookbook 'yum'
cookbook 'nginx'
cookbook 'users'

Dir[File.dirname(__FILE__)+"/site-cookbooks/*"].each do |book|
  cookbook File.basename(book), path: book
end
