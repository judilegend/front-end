<template>
  <div class="flex flex-col justify-center h-screen">
    <div class="w-full max-w-md bg-white rounded-lg shadow-md p-6">
      <form class="flex flex-col">
        <input
          placeholder="Name"
          class="bg-gray-100 text-gray-900 border-0 rounded-md p-2 mb-4 focus:bg-gray-200 focus:outline-none focus:ring-1 focus:ring-blue-500 transition ease-in-out duration-150"
          type="text"
        />
        <input
          placeholder="Decription"
          class="bg-gray-100 text-gray-900 border-0 rounded-md p-2 mb-4 focus:bg-gray-200 focus:outline-none focus:ring-1 focus:ring-blue-500 transition ease-in-out duration-150"
          type="text"
        />
        <select
          name="status"
          id="stat"
          class="bg-gray-100 text-gray-900 border-0 rounded-md p-2 mb-4 focus:bg-gray-200 focus:outline-none focus:ring-1 focus:ring-blue-500 transition ease-in-out duration-150"
        >
          <option value="a faire">A faire</option>
          <option value="a faire">en cours</option>
          <option value="a faire">Termine</option>
        </select>
        <input
          placeholder="Pid_person"
          class="bg-gray-100 text-gray-900 border-0 rounded-md p-2 mb-4 focus:bg-gray-200 focus:outline-none focus:ring-1 focus:ring-blue-500 transition ease-in-out duration-150"
          type="text"
        />
        <button
          class="bg-gradient-to-r from-slate-700 to-slate-600 text-white font-bold py-2 px-4 rounded-md mt-4 hover:bg-slate-500 hover:to-slate-700 transition ease-in-out duration-150"
          type="submit"
        >
          Save changes
        </button>
      </form>
    </div>
  </div>
</template>
