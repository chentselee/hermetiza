<script lang="ts">
  interface Principle {
    name: string
    description: string
  }

  const principles: Principle[] = [
    {
      name: 'The principle of mentalism',
      description: 'The All is Mind; the universe is Mental.',
    },
    {
      name: 'The principle of correspondence',
      description: 'As above, so below; as below, so above.',
    },
    {
      name: 'The principle of vibration',
      description: 'Nothing rests; everything moves; everything vibrates.',
    },
    {
      name: 'The principle of polarity',
      description: `Everything is dual; everything has poles; everything has its pair of opposites; like and unlike are the same; opposites are identical in nature, but different in degree; extremes meet; all truth are but half-truths; all paradoxes may be reconciled.
      `,
    },
    {
      name: 'The principle of rhythm',
      description: `
      Everything flows, out and in; everything has its tides; all things rise and fall; the pendulum-swing manifests in everything; the measure of the swing to the right is the measure of the swing to the left; rhythm compensates.
      `,
    },
    {
      name: 'The principle of cause and effect',
      description: `
      Every cause has its effect; every effect has its cause; everything happens
      according to law; chance is but a name for law not recognized; there are
      many planes of causation, but nothing escapes the law.
      `,
    },
    {
      name: 'The principle of gender',
      description: `
      Gender is in everything; everything has its masculine and feminine
      principles; gender manifests on all planes.
      `,
    },
  ]
</script>

<main class="max-w-6xl mx-auto pt-8">
  <h1 class="text-5xl font-bold text-center font-serif">Hermetiza</h1>
  <dl class="mt-10 space-y-5">
    {#each principles as principle}
      <div class="font-serif">
        <dt class="text-xl font-bold">{principle.name}</dt>
        <dd class="mt-1 text-lg font-light italic">{principle.description}</dd>
      </div>
    {/each}
  </dl>
</main>
