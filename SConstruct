env = Environment()

resume = env.PDF(target=['resume.pdf'], source=['resume.tex'])
cover = env.PDF(target=['cover_letter.pdf'], source=['cover_letter.tex'])

references = env.PDF(target='references.pdf', source=['references.tex'])
env.Clean(resume, 'references.bbl')
env.Clean(resume, 'references.blg')
