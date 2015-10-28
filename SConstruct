env = Environment()

resume = env.PDF(target='resume.pdf', source='resume.tex')
references = env.PDF(target='references.pdf', source='references.tex')
env.Clean(resume, 'references.bbl')
env.Clean(resume, 'references.blg')
