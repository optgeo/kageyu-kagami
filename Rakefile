task :build do
  sh <<-EOS
charites build style.yml docs/style.json
  EOS
end

task :host do
  sh "budo -d docs"
end

