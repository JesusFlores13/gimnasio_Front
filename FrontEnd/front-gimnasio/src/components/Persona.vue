<template>
    <form>

        <div class="grid gap-12 mb-12 sm:grid-cols-2 mt-8 ">
            <div>
                <label class="px-1 block text-sm uppercase text-gray-500 mb-2 font-extrabold">Nombre</label>
                <input type="text"
                    class="font-bold hover:bg-blue-100 focus:bg-blue-100 rounded-sm shadow-sm  focus:ring-0 w-full px-3 py-2 mb-5 border border-gray-300 rounded-xl placeholder-gray-400"
                    placeholder="Nombre">

            </div>
            <div>
                <label class="px-1 block text-sm uppercase text-gray-500 mb-2 font-extrabold">Primer
                    Apellido</label>
                <input type="text"
                    class="font-bold hover:bg-blue-100 focus:bg-blue-100 rounded-sm shadow-sm  focus:ring-0 w-full px-3 py-2 mb-5 border border-gray-300 rounded-xl placeholder-gray-400"
                    placeholder="Primer apellido ">
            </div>
            <div>
                <label class="px-1 block text-sm uppercase text-gray-500 mb-2 font-extrabold">Segundo Apellido
                </label>
                <input type="text"
                    class="font-bold hover:bg-blue-100 focus:bg-blue-100 rounded-sm shadow-sm  focus:ring-0 w-full px-3 py-2 mb-5 border border-gray-300 rounded-xl placeholder-gray-400"
                    placeholder="Segundo Apellido">
            </div>
            <div>
                <label class="px-1 block text-sm uppercase text-gray-500 mb-2 font-extrabold">Titulo de cortesia
                </label>
                <input type="text"
                    class="font-bold hover:bg-blue-100 focus:bg-blue-100 rounded-sm shadow-sm  focus:ring-0 w-full px-3 py-2 mb-5 border border-gray-300 rounded-xl placeholder-gray-400"
                    placeholder="Mr.">
            </div>
            <div>
                <label class="px-1 block text-sm uppercase text-gray-500 mb-2 font-extrabold">Fecha de
                    nacimiento</label>
                <input type="date"
                    class="font-bold hover:bg-blue-100 focus:bg-blue-100 rounded-sm shadow-sm  focus:ring-0 w-full px-3 py-2 mb-5 border border-gray-300 rounded-mxl placeholder-gray-400">
            </div>
            <div>
                <label class="px-1 block text-sm uppercase text-gray-500 mb-2 font-extrabold">Foto</label>
                <input type="file"
                    class="font-bold hover:bg-blue-100 focus:bg-blue-100 rounded-sm shadow-sm  focus:ring-0 w-full px-3 py-2 mb-5 border border-gray-300 rounded-xl placeholder-gray-400">
            </div>
            <div>
                <label class="px-1 block text-sm uppercase text-gray-500 mb-2 font-extrabold">Selecciona el
                    genero</label>
                <select
                    class="font-bold hover:bg-blue-100 focus:bg-blue-100 rounded-sm shadow-sm  focus:ring-0 w-full px-3 py-2 mb-5 border border-gray-300 rounded-xl placeholder-gray-400">
                    <option>-- Selecciona genero --</option>
                    <option>Hombre</option>
                    <option>Mujer</option>
                    <option>Otro</option>
                </select>
            </div>
            <div>
                <label class="px-1 block text-sm uppercase text-gray-500 mb-2 font-extrabold">Selecciona tipo de
                    sangre</label>
                <select
                    class="font-bold hover:bg-blue-100 focus:bg-blue-100 rounded-sm shadow-sm  focus:ring-0 w-full px-3 py-2 mb-5 border border-gray-300 rounded-xl placeholder-gray-400">
                    <option>-- Selecciona tipo de sangre --</option>
                    <option>A+</option>
                    <option>A-</option>
                    <option>B+</option>
                    <option>B-</option>
                    <option>AB+</option>
                    <option>AB-</option>
                    <option>O+</option>
                    <option>O-</option>
                </select>
            </div>
        </div>
    </form>
    
</template>