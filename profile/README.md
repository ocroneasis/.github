## contents
| field | topic | state |
| ----- | ----- | ----- |
|  <span style="color:violet"> Graphics </span>  |  OpenGL            |  <span style="color:blue">WIP</span>  |
|  <span style="color:violet"> Graphics </span>  |  Vulkan            |  <span style="color:gray">LKD</span>  |
|  <span style="color:violet"> Graphics </span>  |  DirectX 12        |  <span style="color:gray">LKD</span>  |
|  <span style="color:violet"> Graphics </span>  |  Soft Renderer     |  <span style="color:orange">DLD</span>  |
|  <span style="color:violet"> Graphics </span>  |  PBR               |  <span style="color:orange">DLD</span>  |
|  <span style="color:violet"> Graphics </span>  |  Ray Tracing (CPU) |  <span style="color:gray">LKD</span>  |
|  <span style="color:violet"> Graphics </span>  |  Ray Tracing (GPU) |  <span style="color:red">NA</span>  |
|  <span style="color:violet"> Graphics </span>  |  Shader            |  <span style="color:orange">DLD</span>  |
|  <span style="color:#54ff7b"> Physics </span>  |  2D Physics        |  <span style="color:orange">DLD</span>  |
|  <span style="color:#54ff7b"> Physics </span>  |  3D Physics        |  <span style="color:gray">LKD</span>  |
|  <span style="color:#54ff7b"> Physics </span>  |  Fluid Mechanics   |  <span style="color:gray">LKD</span>  |
|  <span style="color:blueviolet"> Parallel Computing </span>  |  OpenCL  |  <span style="color:gray">LKD</span>  |
|  <span style="color:blueviolet"> Parallel Computing </span>  |  CUDA    |  <span style="color:red">NA</span>  |
|  <span style="color:yellowgreen"> Architecture </span>  |  Game Engine Design |  <span style="color:orange">DLD</span>  |
|  <span style="color:yellowgreen"> Architecture </span>  |  Design Pattern |  <span style="color:orange">DLD</span>  |
|  <span style="color:indigo"> P.L Theory </span>  |  Compiler Design |  <span style="color:gray">LKD</span>  |
|  <span style="color:indigo"> P.L Theory </span>  |  Interpreter Design |  <span style="color:orange">DLD</span>  |
|  <span style="color:brown"> Asynchronous </span>  | Threading |  <span style="color:orange">DLD</span>  |
|  <span style="color:#33699a"> Others </span>  | Genetic Algorithm |  <span style="color:gray">LKD</span>  |
|  <span style="color:#33699a"> Others </span>  | DL |  <span style="color:gray">LKD</span>  |
|  <span style="color:#33699a"> Others </span>  | Networking |  <span style="color:gray">LKD</span>  |
|  <span style="color:#33699a"> Others </span>  | x64 Assembly |  <span style="color:orange">DLD</span>  |


| state | desc |
| ----- | ---- |
| <span style="color:green">FIN</span>    | Finished |
| <span style="color:blue">WIP</span>     | Work In Progress |
| <span style="color:orange">DLD</span>   | Delayed |
| <span style="color:gray">LKD</span>     | Locked |
| <span style="color:red">NA</span>       | Not Available |

## features intended
<details>
<summary><b>OpenGL</b></summary>

### Basic
- Window Setup
- Input Guide
- Simple Triangle
- Colorful Triangle
- Colorful Quad
- Transformation
- MVP
- Camera
- Texturing
- Going 3D

### Intermediate
- Frame Buffer
- Depth Testing
- Stencil Testing
- Scissor
- Culling
- Skybox
- Billboard
- Directional Light
- Point Light
- Spot Light
- Specular Mapping
- Normal Mapping
- Parallax Mapping
- Shadow Mapping with Directional Light
- Shadow Mapping with Point Light
- Shadow Mapping with Spot Light
- Model Loading
- Instancing
- Batch Rendering
- Uniform Buffer
- Geometry Shader
- Tessellation Shader

### Advanced
- Deferred Rendering
- Z Pre-Pass
- Environmental Mapping
- Reflection
- Refraction
- Fresnel Effect
- HDR (High Dynamic Range) & Tone Mapping
- Bloom & Physically Based Bloom
- PBR (Physically Based Rendering)
- IBL (Image Based Rendering) & Irradiance System
- Skeletal Animation & Procedural Animation
- Occlusion Culling
- SSAO (Screen Space Ambient Occlusion)
- Global Illumination & Voxel Cone Tracing

### Extra
- Toon Shading
- Font Rendering & SDF (Signed Distance Field)
- Bezier Spline & Spline Camera
- Unprojection & Mouse Picking
- Compute Shader
- GPU Particle System
- SSR (Screen Space Reflection)
- SSGI (Screen Space Global Illumination)
- HBAO (Horizon Based Ambient Occlusion)
- FXAA (Fast Approximate Anti-Aliasing)
- Depth Peeling
- Atmospheric Scattering
- Water Caustics & FFT (Fast Fourier Transform)
- Terrain Generation
- Indirect Buffer
- Pixel Buffer
- Transform Feedback Buffer
- Shader Storage Buffer
- Buffer Mapping
- DSA (Direct State Access)
- Channel Packing & Unpacking
- CSM (Cascaded Shadow Mapping)
- VSM (Variance Shadow Mapping)
- Shadow Volume
- Volumetric Lighting
- Bindless Texture
- Clustered Shading
- Tile Based Shading
- DoF (Depth of Field)
- SSS (Sub-Surface Scattering)
- Motion Blur
- Ray Tracing
- Path Tracing
- Ray Marching
- Occlusion Query
- BSP (Binary Space Partitioning)
- Octree
- BVH (Bounding Volume Hierarchy)
- Greedy Meshing
- Decal Rendering
- Fur Rendering
- Edge Detection

</details>

<details>
<summary><b>2D Physics</b></summary>

### Basic
- Linear Motion
- Angular Motion
- Numerical Integrators
- Fundamental Collision Detection & MTV (Minimum Translation Vector)

### Algorithm
- SAT (Separated Axis Theorem)
- GJK (Gilbert-Johnson-Keerthi) & EPA (Expanding Polytope Algorithm)
- SAP (Sweep And Prune)
- Centroid Calculation
- Moment of Inertia Calculation

### Data Structure
- Quadtree

### Core
- Coefficient of Restitution
- Static & Dynamic Friction
- Manifold
- Friction
- Impulse & Tangent Impulse

### Option
- Accumulated Impulse
- Position Correction
- Sub Stepping

### Optimizing
- Partitioning with Quadtree
- SAP
- Remove Tunneling

### Extra
- Find Convex Hull
- Triangulation
- Joint
- Relative Force
- Ray Casting
- Mass-Spring Damper System
- Soft Body & Shape Matching
- Shape Composition
- Collision Layer & Mask

</details>

<details>
<summary><b>Threading</b></summary>

### Thread
- std::thread
- std::jthread
- thread_local

### Mutex
- std::mutex
- std::shared_mutex
- std::timed_mutex
- std::recursive_mutex

### Coroutine
- Traits
- Handle
- Generator
- Suspend
- Awaitable

### Extra
- std::conditional_variable
- std::future
- std::promise
- std::async
- std::packaged_task
- std::barrier
- std::latch
- std::atomic
- std::unique_lock
- std::scoped_lock
- std::lock_guard
- Semaphore
- Spin Lock
- Reader-Writer Lock
- Thread Pool

### Implementation
- Thread-Safe Singleton
- Thread-Safe Logger
- Thread-Safe Timer
- Thread-Safe Cache
- Notify Queue
- safe_ptr

</details>
