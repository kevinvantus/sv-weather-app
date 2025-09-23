<div class="search-ctr">
  <div class="search-input-wrapper">
    <input
      type="text"
      class="search-input text-5 md"
      placeholder="Search for a place..."
    />
  </div>
  <button type="button" class="search-btn text-5 md">Search</button>
</div>

<style>
  .search-ctr {
    display: flex;
    flex-direction: column;
    gap: var(--size-150);
  }

  :where(.search-btn, .search-input) {
    padding: var(--size-200) var(--size-300);
  }

  .search-btn {
    background-color: var(--blue-500);
    border-radius: var(--radius-12);
  }

  .search-btn:hover {
    background-color: var(--blue-700);
  }

  .search-btn:where(:focus-visible, :focus, :active) {
    outline: 3px solid var(--blue-500);
    outline-offset: 3px;
  }

  .search-input-wrapper {
    position: relative;
    background-image: url("/public/assets/images/icon-search.svg");
    background-color: var(--neutral-800);
    background-repeat: no-repeat;
    border-radius: var(--radius-12);
    background-position: var(--size-300);
    overflow: hidden;
    transition: background-color 0.25s cubic-bezier(0.68, -0.55, 0.265, 1.55);
  }

  .search-input {
    background: transparent;
    width: 100%;
    border: none;
    outline: none;
    padding-inline-start: 60px;
  }

  .search-input-wrapper:hover {
    background-color: var(--neutral-700);
  }

  .search-input-wrapper:focus-within {
    outline: 2px solid var(--neutral-0);
    outline-offset: 3px;
    background-color: var(--neutral-800);
  }

  ::placeholder {
    color: var(--neutral-200);
  }

  @media screen and (min-width: 768px) {
    .search-ctr {
      flex-direction: row;
      width: 100%;
      max-width: 41rem;
      margin-inline: auto;
    }

    .search-input-wrapper {
      flex: 1;
    }
  }
</style>
