source 'https://rubygems.org'

# Specify Ruby version if you use one (uncomment and set if needed)
# ruby '2.7.6'

# Keep plugins in a group so Jekyll-related gems are obvious
group :jekyll_plugins do
  # Bump Jekyll to a modern 4.x series for better compatibility and security.
  # '~> 4.2' allows 4.2.x but prevents 5.0 breaking changes.
  gem 'jekyll', '~> 4.2'

  # kramdown 2.x series is compatible with Jekyll 4 and avoids older rexml pulls.
  # Use a conservative constraint that allows security/patch updates.
  gem 'kramdown', '~> 2.4'

  # Rouge 3.x+ for syntax highlighting (compatible with Jekyll 4)
  gem 'rouge', '~> 3.26'

  # jekyll plugins used by the site
  gem 'jekyll-paginate', '~> 1.1'
  gem 'jekyll-gist', '~> 1.4'
  gem 'jekyll-watch', '~> 2.2'

  # Ensure rexml is at or above the patched version required by Dependabot
  gem 'rexml', '>= 3.3.9'
end

# Optional: lock bundler version when committing Gemfile.lock (Bundler will write this)
# gem 'bundler', '~> 2.3'
