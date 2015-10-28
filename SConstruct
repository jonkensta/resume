env = Environment()

resume = env.PDF(target='resume.pdf', source='resume.tex')
env.Clean(resume, 'references.bbl')
env.Clean(resume, 'references.blg')

references = env.PDF(target='references.pdf', source='references.tex')

cover_letter = env.PDF(targets='cover_letter.pdf', source='cover_letter.tex')
