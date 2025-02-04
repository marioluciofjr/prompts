# Prompt que gera um prompt para utilizar na plataforma [Riffusion](https://www.riffusion.com/)

OBS: O prompt utilizado em `<exemplo></exemplo>` é do [Márcio Campos](https://suno.com/@marciocampos)

```
<tema>
{COLOQUE AQUI UM TEMA}
</tema>

<exemplo>
<SONG_PROMPT>
    <HEADER>
        [GENRE: Deep House x Classical Music]
        [STYLE: Danceable, Organic, Hypnotic]
        [MOOD: Sensual, Mysterious, Dreamy]
        [INSTRUMENTATION: Smooth Saxophone, Melodic Violin, Emotional Pianos, Ethereal Pads]
        [TEMPO: 120 BPM]
        [PRODUCTION: Organic Percussion, Spatial Textures, Deep Groove]
        [INFLUENCES: Nicolas Jaar, Kora, Armen Miran]
    </HEADER>

    <ATMOSPHERE_LAYER>
        <ARTISTIC_INFLUENCE>
            [Deep house minimalism incorporating classical harmonies and jazzy nuances. The organic instrumentation should naturally interact with electronic elements, creating a balanced fusion of both styles.]
        </ARTISTIC_INFLUENCE>
        <INSTRUMENTAL_DYNAMICS>
            [Transitions between sections should be smooth, ensuring that acoustic and electronic elements complement rather than compete. The groove should be hypnotic, with progressive variations to maintain listener immersion.]
        </INSTRUMENTAL_DYNAMICS>
    </ATMOSPHERE_LAYER>

    <SONG_MODULES>
        <INTRO>
            [A soft piano introduces a slow and emotional melody, accompanied by atmospheric pads.]
            [Percussion starts subtly, creating an immersive environment.]
        </INTRO>

        <BUILD_UP_1>
            [Saxophone enters ethereally, blending into the groove with light reverbs.]
            [Additional synthesizer layers bring texture and depth.]
        </BUILD_UP_1>

        <DROP_1>
            [Deep bassline and immersive groove merge, maintaining the smooth flow of deep house.]
            [Violins add melodic expressiveness, contrasting with electronic timbres.]
        </DROP_1>

        <BREAKDOWN>
            [Percussion fades out, leaving space for expansive strings and pads.]
            [The composition should create an introspective and ethereal moment before the energy rebuilds.]
        </BREAKDOWN>

        <BUILD_UP_2>
            [Hi-hats gain intensity, ascending synthesizers build anticipation.]
            [Percussion gradually returns, preparing for the final transition.]
        </BUILD_UP_2>

        <DROP_2>
            [The full beat returns, with violins and saxophone flowing together, creating a sophisticated groove.]
            [The fusion of classical and electronic elements should be perceived organically.]
        </DROP_2>
    </SONG_MODULES>

    <OUTPUT_EXPECTED>
        [The generated track should be a balanced fusion of deep house and classical music.]
        [The acoustic instrumentation should sound authentic and well-integrated into the electronic context.]
        [The groove must maintain a continuous flow, avoiding abrupt elements that break immersion.]
        [The final result should be suitable for sophisticated dance floors, chill environments, and immersive experiences.]
    </OUTPUT_EXPECTED>

</SONG_PROMPT>
</exemplo>

<tarefa>
1. Refaça o prompt do exemplo de acordo com o tema. Lembrando que as instruções do prompt iniciarão com colchetes e terminarão com colchetes, delimitando todas as informações necessárias do prompt, tendo como formato de saída em markdown: [INTRO], [VERSE 1], [VERSE 2], [CHORUS], [CHORUS], [VERSE 1], [VERSE 2], [BRIDGE], [CHORUS], [CHORUS] e {End}.

2. Traduza o prompt final para o inglês com o mesmo formato de saída em markdown.
</tarefa>
```
