squash-action: True
imitation-weight: 0.5
LLC-frequency: 500
interpolation: False
max-episode-num: 5000000
critic-l2-reg: 0.0003
filter-torque: False
joint-interpolation: True
loss-output-bound-coeff: 0.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-num: 4
total-step-num: 2500000000
expert-index: None
critic-weight-decay: 1e-06
render-eval: False
actor-lr: 0.0003
replay-buffer-size: 1000000
n-step: 1
gamma: 0.955
record-start-size: 10000.0
actor-l2-reg: 0.0003
Physics-frequency: 1000
actor-layer-size: [256, 256]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
env-id: HumanoidBalanceFilter-v0
epoch-step-num: 5000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
dsr-gait-period: 0.6
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
rollout-step-num: 1
critic-lr: 0.0003
test-num: 4
max-step-num: 2500000000
critic-layer-size: [256, 256]
loss-output-diff-coeff: 0
reward-scale: 0.1
action-dim: 12
dsr-gait-freq: 1.667
max-path-num: 20
state-dim: 23
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
train-step-num: 1
HLC-frequency: 25
gating-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
actor-weight-decay: 1e-06
gating-layer-size: [32, 32]
task-weight: 0.5
bullet-default-PD: False
max-path-step: 5000
critic-activation-fn: ['relu', 'relu', 'None']
tau: 0.001
max-test-time: 10
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-ratio: 1
loss-entropy-coeff: 0.0
gating-index: None
loss-output-smooth-coeff: 0.5
batch-size: 128
prioritized-exp-replay: True
filter-action: True
epoch-num: 500
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-activation-fn: ['relu', 'relu', 'None']
